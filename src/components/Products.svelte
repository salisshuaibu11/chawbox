<script>
	let isLiked = false;
	let element;

	export let title = 'Featured Products';
	export let subTitle = 'Here’s where Chaw members are having the most luck';

	const toggleLike = () => {
		isLiked = !isLiked;
		console.log(isLiked);
		const iconString = isLiked ? 'icon-heart' : 'icon-heart-outlined';
		element.querySelector('use').setAttribute('href', `/icons.svg#${iconString}`);
	};
</script>

<section class="mt-24 w-screen p-8">
	<div class="w-full sm:w-11/12 md:w-5/6 mx-auto">
		<div class="flex flex-col text-left justify-start items-start">
			<span class="text-green-600 text-2xl font-bold">{title}</span>
			<h3 class="mt-2 text-lg text-gray-500">
				{subTitle}
			</h3>
		</div>

		<div class="grid lg:grid-cols-4 md:grid-cols-3 justify-items-center mt-10 text-center">
			<article class="feature group h-fit relative text-left p-3 bg-white shadow-md">
				<div class="relative">
					<a href="/products/1234"
						><img class="m-auto w-full h-full" src="/groceries/date.png" alt="E Farm" /></a
					>
					<div
						class="bg-black absolute w-full h-10 bottom-0 flex items-center justify-center group-hover:opacity-70 text-lg opacity-0 text-white"
					>
						<button>Add To Cart</button>
					</div>
				</div>
				<div
					on:click={toggleLike}
					class="bg-white cursor-pointer absolute top-4 right-5 p-2 rounded-full opacity-0 group-hover:opacity-70"
				>
					<svg bind:this={element} class="likes__icon">
						<use href="/icons.svg#icon-heart-outlined" />
					</svg>
				</div>
				<img class="absolute top-0 -left-0" src="/percentage.png" alt="Percentage taken" />
				<h3 class="">
					<a href="/products/1234">
						<h5 class="py-2 font-medium">0.1kg teaspoonful Almond Seed</h5>
						<h5 class="text-slate-500">A one-line sub-text should be...</h5>
					</a>
				</h3>
				<div class="flex space-x-1 py-3">
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star-6.svg" alt="" />
				</div>
				<span class="font-bold">
					<span>N400.00</span>
					<span>/kg</span>
					<span class="text-red-400 line-through ml-4">N550.00</span>
				</span>
			</article>
		</div>

		<div
			class="flex m-auto text-center cursor-pointer space-x-3 justify-center mt-5 w-2/4 items-center"
		>
			<a class="flex space-x-6 items-center" href="/products">
				<h4 class="text-2xl uppercase font-black text-gray-800">Explore All</h4>
				<svg
					class="slide-bck-left"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<g clip-path="url(#clip0_561_5121)">
						<path
							d="M18.5 7.49695L23.5 12.4969L18.5 17.4969"
							stroke="#031009"
							stroke-width="1.5"
							stroke-linecap="round"
							stroke-linejoin="round"
						/>
						<path
							d="M23.5 12.4969H0.5"
							stroke="#031009"
							stroke-width="1.5"
							stroke-linecap="round"
							stroke-linejoin="round"
						/>
					</g>
					<defs>
						<clipPath id="clip0_561_5121">
							<rect width="24" height="24" fill="white" />
						</clipPath>
					</defs>
				</svg>
			</a>
		</div>
	</div>
</section>

<style>
	.likes__icon {
		fill: #f59a83;
		height: 1.5rem;
		width: 1.5rem;
	}
</style>
