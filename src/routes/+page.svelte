<script>
    import About from "./About.svelte";
	import Hero from "./Hero.svelte";
	import Contact from "./Contact.svelte";
	import Footer from "./Footer.svelte";
</script>

<svelte:head>
	<title>Afya Innovation Lab - Igniting Medical Innovation.</title>

	<link rel="preconnect" href="https://fonts.googleapis.com" />

	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

	<link
		href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&display=swap"
		rel="stylesheet"
	/>

	<link
		href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
		rel="stylesheet"
		integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
		crossorigin="anonymous"
	/>
</svelte:head>

<Hero />

<About />

<Contact />

<Footer/>


