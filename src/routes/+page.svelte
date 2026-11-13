<script>
import Map from "#lib/components/Map.svelte";
</script>

<svelte:head>
    <title>Jan 80 Jaar!!</title>
</svelte:head>

<main class="w-full min-h-screen flex items-center">
    <div class="w-full max-w-7xl bg-white p-4 mx-auto rounded-lg">
        <h1 class="text-3xl  font-bold">Jan 80 Jaar!!</h1>
        <div class="flex gap-2">
            <!-- <img src="" alt=""/> -->
            <div>
                <h2 class="font-bold text-xl">Adres:</h2>
                <p>Badweg 10, 3312 AB Dordrecht</p>
                <Map
                    source="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2466.4416053771783!2d4.690549513320938!3d51.816362971767724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c429ea3187b7f3%3A0x660065852aeced74!2sEetcaf%C3%A9%20het%20Puntje!5e0!3m2!1sen!2snl!4v1794481645061!5m2!1sen!2snl"
                />
            </div>
        </div>
    </div>
</main>
