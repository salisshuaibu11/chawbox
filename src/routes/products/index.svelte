<script>
    import TopGroceries from "../../components/Products.svelte";
    import DealsOfTheDay from "../../components/Products.svelte";
    import FeaturedProducts from "../../components/Products.svelte";
    import ExclusiveProducts from "../../components/Products.svelte";
</script>

<svelte:head>
    <title>Products</title>
</svelte:head>

<DealsOfTheDay title="Deals of the day" subTitle="Here’s where Chaw members are having the most luck."/>
<TopGroceries title="Top Groceries" subTitle="Here’s where Chaw members are having the most luck.
" />
<FeaturedProducts title="Featured Products" subTitle="Here’s where Chaw members are having the most luck.
"/>
<ExclusiveProducts title="Exclusive Products" subTitle="Here’s where Chaw members are having the most luck.
" />