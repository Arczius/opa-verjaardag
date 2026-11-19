<script>
import Text from "./Text.svelte";

import H1 from "#lib/components/text/H1.svelte";
import Image from "#lib/components/Image.svelte";
</script>

<svelte:head>
    <title>Jan 80 Jaar!!</title>
    <meta name="description" content="Jan wordt 80 Jaar, komt u ook?"/>
    <meta name="author" content="Regina de Koning"/>
</svelte:head>

<main class="w-full min-h-screen flex items-center">
    <div class="w-full max-w-7xl bg-white p-4 mx-auto rounded-lg">

    <H1>Jan 80 Jaar!!</H1>
        <div class="flex gap-2 flex-col-reverse md:flex-row">
            <div class="w-full lg:w-1/2">
                <Text/>
            </div>

            <div class="flex justify-center w-full lg:w-1/2">
                <Image src="/opa.jpeg"  alt=""/>
            </div>
        </div>
    </div>
</main>
