<script>
	import GetChawBox from '$lib/GetChawBox.svelte';
    import TopGroceries from "../../components/Products.svelte";
    import DealsOfTheDay from "../../components/Products.svelte";
    import FeaturedProducts from "../../components/Products.svelte";
    import ExclusiveProducts from "../../components/Products.svelte";
</script>

<section class="-mt-24 w-screen bg-gray-100 p-8">
	<div class="w-full sm:w-11/12 md:w-5/6 mx-auto">
		<div class="block mb-24 flex justify-center flex-wrap items-center leading-10">
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
			<span class="block">
				<a href="#" class="text-green-600 font-bold text-lg mx-3">Link</a>
			</span>
		</div>

		<div class="bg-white mx-auto p-4 grid grid-cols-1 lg:grid-cols-3 gap-4">
			<div
				class="col-span-2 h-[360px] md:h-[540px] overflow-hidden bg-[url('/food.jpg')] bg-no-repeat bg-cover bg-center bg-blend-multiply bg-green-300 w-full"
			>
				<div class="flex justify-start items-start flex-1 flex-col px-4 md:px-8 mt-24 md:mt-48">
					<h1 class="text-white font-black text-4xl">
						Get The Most Of Our Special Deals Curated Just For You
					</h1>
					<div class="mt-4">
						<a
							href=""
							class="bg-gray-900 font-bold text-xl opacity-50 text-white border border-gray-50 py-2 px-6 rounded"
							>Shop Now</a
						>
					</div>
				</div>
			</div>
			<div class="flex justify-between items-center flex-row lg:flex-col lg:flex-1">
				<div
					class="h-[180px] md:h-[265px] mr-4 lg:mr-0 overflow-hidden bg-[url('/food.jpg')] bg-no-repeat bg-cover bg-center bg-blend-multiply bg-green-300 w-full"
				>
					<div class="flex justify-start items-start flex-1 flex-col px-4 md:px-8 mt-8 md:mt-24">
						<h1 class="text-white font-black text-2xl">
							Get The Most Of Our Special Deals Curated
						</h1>
					</div>
				</div>
				<div
					class="h-[180px] md:h-[265px] -mr-4 lg:mr-0 overflow-hidden bg-[url('/food.jpg')] bg-no-repeat bg-cover bg-center bg-blend-multiply bg-green-300 w-full"
				>
					<div class="flex justify-start items-start flex-1 flex-col px-4 md:px-8 mt-8 md:mt-24">
						<h1 class="text-white font-black text-2xl">
							Get The Most Of Our Special Deals Curated
						</h1>
					</div>
				</div>
			</div>
		</div>

		<div class="mt-12 mx-auto place-content-center grid grid-cols-1 md:grid-cols-3 gap-4">
			<div class="flex justify-start items-start p-2">
				<img src="/green-truck.png" alt="Truck" class="mr-2" />
				<div>
					<h2 class="font-semibold text-gray-800 text-lg mb-2">Free Delivery</h2>
					<span class="text-gray-400 font-normal text-md"
						>Get free delivery for all your orders over NGN15,000</span
					>
				</div>
			</div>
			<div class="flex justify-start items-start p-2">
				<img src="/green-card.png" alt="Card" class="mr-2" />
				<div>
					<h3 class="font-semibold text-gray-800 text-lg mb-2">Secure Payment</h3>
					<span class="text-gray-400 font-normal text-md"
						>100% secure payment on all transactions</span
					>
				</div>
			</div>
			<div class="flex justify-start items-start p-2">
				<img src="/green-support.png" alt="Support" class="mr-2" />
				<div>
					<h3 class="font-semibold text-gray-800 text-lg mb-2">24/7 Support</h3>
					<span class="text-gray-400 font-normal text-md"
						>Get 24/7 access to our fully dedicated support team
					</span>
				</div>
			</div>
		</div>
	</div>
</section>

<DealsOfTheDay
	title="Deals of the day"
	subTitle="Here’s where Chaw members are having the most luck."
/>
<TopGroceries
	title="Top Groceries"
	subTitle="Here’s where Chaw members are having the most luck.
"
/>
<FeaturedProducts
	title="Featured Products"
	subTitle="Here’s where Chaw members are having the most luck.
"
/>
<ExclusiveProducts
	title="Exclusive Products"
	subTitle="Here’s where Chaw members are having the most luck.
"
/>
<GetChawBox />
