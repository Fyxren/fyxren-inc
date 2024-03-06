<script>
	import Banner from "$lib/components/elements/Banner.svelte";
	import Clients from "$lib/components/elements/Clients.svelte";
	import Footer from "$lib/components/elements/Footer.svelte";
	import Hero from "$lib/components/elements/Hero.svelte";
	import Team from "$lib/components/elements/Team.svelte";

</script>

<svelte:head>
    <title>Fyxren Inc.</title>
    <meta name="description" content="The place to be for all your needs. Only the best services and products for you." />
    <meta name="keywords" content="Fyxren, Fyxren Inc., Fyxren Inc. 2024, Fyxren 2024, Fyxren Inc. All rights reserved." />
    <meta name="author" content="Fyxren Inc." />
    <meta name="robots" content="noindex, nofollow" />
    <meta name="theme-color" content="#112" />

    <meta property="og:title" content="Fyxren Inc." />
    <meta property="og:description" content="The place to be for all your needs. Only the best services and products for you." />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://fyxren.com" />
    <meta property="og:image" content="https://github.com/Fyxren.png" />
    <meta property="og:site_name" content="Fyxren Inc." />
    <meta property="og:locale" content="en_US" />
    
    <meta name="twitter:card" content="summary" />
    <meta name="twitter:site" content="@Fyxren" />
    <meta name="twitter:creator" content="@Fyxren" />
    <meta name="twitter:title" content="Fyxren Inc." />

</svelte:head>

<div class="h-full">
    <Banner />
    <Hero />
    <Team />
    <Clients />
    <Footer />
</div>