<script>
	import Commerce from '$lib/Commerce.svelte';
	import CustomerReviews from '$lib/CustomerReviews.svelte';
	import Farms from '$lib/Farms.svelte';
	import GetChawBox from '$lib/GetChawBox.svelte';
	import Header from '$lib/Header.svelte';
	import Services from '$lib/Services.svelte';
	import WhyChawBox from '$lib/WhyChawBox.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<Header />
<Services />
<Commerce />
<Farms />
<GetChawBox />
<WhyChawBox />
<CustomerReviews />
<Footer />
