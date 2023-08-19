<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import '../app.css';
</script>

<svelte:head>
	<title>Cloud12</title>
	<meta name="description" content="Personal website" />
</svelte:head>

<div class="container mx-auto py-2">
	<div class="pb-8">
		<Header />
	</div>
	<slot />
	<div class="pt-8">
		<Footer />
	</div>
</div>
