<script lang="ts">
    import { onMount } from 'svelte';
    import confetti from 'canvas-confetti';


    let {
        particleCount = 300,
        spread = 150,
        startVelocity = 100,
        gravity = 0.8,
        ticks = 400,
        angle = 270,
        yAxis = -0.3
    } = $props();

    onMount(() => {

        for (let x = 0; x <= 1; x += 0.05) {
            confetti({
                particleCount: particleCount,
                spread: spread,
                startVelocity: startVelocity,
                gravity: gravity,
                ticks: ticks,
                angle: angle,
                origin: {
                    x,
                    y: yAxis
                },
                zIndex: 9999,
                disableForReducedMotion: true
            });
        }
    });
</script>
