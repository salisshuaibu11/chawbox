<script>
	import Footer from '../../lib/Footer.svelte';
	import Header from '../../components/Header.svelte';
</script>

<Header />

<main class="px-14 md:px-28 lg:px-56">
	<slot></slot>
</main>

<Footer />
