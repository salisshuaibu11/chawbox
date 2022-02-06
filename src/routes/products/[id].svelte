<script>
	import Accordion from "$lib/Accordion.svelte";
	import Tabs from "$lib/Tabs.svelte";

	let isLiked = false;
    let element;

    const toggleLike = () => {
        isLiked = !isLiked
        console.log(isLiked)
        const iconString = isLiked ? 'icon-heart' : 'icon-heart-outlined';
        element.querySelector("use").setAttribute('href', `/icons.svg#${iconString}`)
    };

	function decrement(e) {
		const btn = e.target.parentNode.parentElement.querySelector(
		'button[data-action="decrement"]'
		);
		const target = btn.nextElementSibling;
		let value = Number(target.value);
		value--;
		target.value = value;
  	}

	function increment(e) {
		const btn = e.target.parentNode.parentElement.querySelector(
		'button[data-action="decrement"]'
		);
		const target = btn.nextElementSibling;
		let value = Number(target.value);
		value++;
		target.value = value;
	}
</script>

<section class="w-screen flex lg:flex-row flex-col px-10">
	<div class="flex-1">
		<img class="min-w-[552px] min-h-[543px]" src="/vegetables.png" alt="" />
		<div class="w-full pt-2 flex space-x-1">
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
			<img src="/cooked.png" alt="" />
		</div>
	</div>
	<div class="flex-1">
		<article class="">
			<div class="flex justify-between">
				<div class="flex items-center">
					<div class="flex space-x-1 py-3 mr-2">
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star-6.svg" alt=""/>
					</div>
					<h4>Rated by 64 people</h4>
				</div>
				<div class="flex items-center space-x-2">
					<svg width="24" height="22" viewBox="0 0 24 22" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path d="M11.9998 20.9323L2.19979 10.8403C1.34029 9.9973 0.7716 8.90247 0.576156 7.71452C0.380713 6.52658 0.568671 5.30726 1.11279 4.23332V4.23332C1.532 3.41957 2.13666 2.71578 2.87797 2.17875C3.61927 1.64173 4.47646 1.28652 5.38033 1.1418C6.2842 0.997074 7.20944 1.06689 8.08136 1.34561C8.95328 1.62432 9.74746 2.10414 10.3998 2.74632L11.9998 4.20532L13.5998 2.74632C14.2522 2.10434 15.0464 1.62471 15.9183 1.34611C16.7902 1.06752 17.7153 0.997764 18.6191 1.14248C19.5229 1.28719 20.3801 1.64232 21.1214 2.17921C21.8627 2.7161 22.4674 3.41973 22.8868 4.23332V4.23332C23.4306 5.30733 23.6184 6.52657 23.4229 7.71444C23.2275 8.90231 22.659 9.99713 21.7998 10.8403L11.9998 20.9323Z" stroke="#5F5F5F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
					</svg>
					<h3>Add to whilslist</h3>
				</div>
			</div>
			<div class="w-full">
				<p class="py-3 text-2xl">0.5kg Freshly Cut Green Vegetables</p>
				<h3 class="text-lg">
					<span class="text-green-700">N450.00</span>
					<span>800.75</span>
				</h3>
				<p class="py-5 font-light">
					An edible portion of a plant. Vegetables are usually grouped according to 
					the portion of the plant that is eaten such as leaves (lettuce)...
				</p>

				<div class="custom-number-input h-10 w-32">
					<div class="flex flex-row h-10 w-full rounded-lg relative bg-transparent mt-1">
					  <button on:click={(e) => decrement(e)} data-action="decrement" class=" bg-gray-300 text-gray-600 hover:text-gray-700 hover:bg-gray-400 h-full w-20 rounded-l cursor-pointer outline-none">
						<span class="m-auto text-2xl font-thin">−</span>
					  </button>
					  <input type="number" class="outline-none focus:outline-none text-center w-full font-semibold text-md hover:text-black focus:text-black  md:text-basecursor-default flex items-center text-gray-700" name="custom-input-number" value="0" />
					<button on:click={(e) => increment(e)} data-action="increment" class="bg-gray-300 text-gray-600 hover:text-gray-700 hover:bg-gray-400 h-full w-20 rounded-r cursor-pointer">
					  <span class="m-auto text-2xl font-thin">+</span>
					</button>
				</div>
				<div class="text-white flex mt-[2rem] space-x-5 w-96">
					<button class="uppercase bg-green-600 py-3 px-5 min-w-[276px]">Add To Cart</button>
					<button class="uppercase text-green-600 py-3 px-5 border min-w-[276px] border-green-400">Get mine now</button>
				</div>
				<div class="flex space-x-4 my-[2.5rem]" id="payments-gatewat">
					<img src="/payments/paypal.png" alt="Paypal" />
					<img src="/payments/mastercard.png" alt="mastercard" />
					<img src="/payments/visa.png" alt="Visa Card" />
					<img src="/payments/verve.png" alt="Verve" />
				</div>
				<div id="testimonial" class="w-screen space-y-5">
					<p class="text-green-700 w-3/4">“This Vegetable is so niceee! I tried it first with doubts buh mehn, they are so fresh!”</p>
					<div class="flex space-x-2">
						<img src="/images/reviews/user1.png" class="w-[5%]" alt="" />
						<div>
							<span class="block">Kemi Ororyo</span>
							<div class="flex space-x-1 py-3 mr-2">
								<img src="/images/rating-star.svg" alt=""/>
								<img src="/images/rating-star.svg" alt=""/>
								<img src="/images/rating-star.svg" alt=""/>
								<img src="/images/rating-star.svg" alt=""/>
								<img src="/images/rating-star-6.svg" alt=""/>
							</div>
						</div>      
					</div>
				</div>
			</div>
		</article>
	</div>
</section>
<Tabs />
<section class="w-screen bg-gray-50 p-10">
	<h2 class="text-2xl pb-4">Customers' Reviews</h2>
	<div class="w-full flex space-x-3">
		<section class="flex-1 space-y-2 px-5 bg-white">
			<article class="w-full text-left p-3 rounded-md">
				<div class="flex justify-between items-center">
					<div class="flex space-x-1 py-3">
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star-6.svg" alt=""/>
					</div>
					<p class="py-5">
						02/04/2022
					</p>
				</div>
				<p class="py-5">“I just wanted to say thank you. Thanks for all the pretty support you give during these issues in the support que forum.”</p>
				<div class="flex space-x-2 items-center">
					<img src="/images/reviews/user1.png" class="" alt="" />
					<span class="block">Adu Lawrence</span>     
				</div>
			</article>
			<hr class="w-full bg-slate-300 h-[1px]"/>
			<article class="w-full text-left p-3 rounded-md">
				<div class="flex justify-between items-center">
					<div class="flex space-x-1 py-3">
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star-6.svg" alt=""/>
					</div>
					<p class="py-5">
						02/04/2022
					</p>
				</div>
				<p class="py-5">“I just wanted to say thank you. Thanks for all the pretty support you give during these issues in the support que forum.”</p>
				<div class="flex space-x-2 items-center">
					<img src="/images/reviews/user1.png" class="" alt="" />
					<span class="block">Adu Lawrence</span>     
				</div>
			</article>
			<hr class="w-full bg-slate-300 h-[1px]"/>
			<article class="w-full text-left p-3 rounded-md">
				<div class="flex justify-between items-center">
					<div class="flex space-x-1 py-3">
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star.svg" alt=""/>
						<img src="/images/rating-star-6.svg" alt=""/>
					</div>
					<p class="py-5">
						02/04/2022
					</p>
				</div>
				<p class="py-5">“I just wanted to say thank you. Thanks for all the pretty support you give during these issues in the support que forum.”</p>
				<div class="flex space-x-2 items-center">
					<img src="/images/reviews/user1.png" class="" alt="" />
					<span class="block">Adu Lawrence</span>     
				</div>
			</article>
		</section>
		<div class="w-[25rem] h-[50%]">
			<div class="w-[360px] h-[253px] bg-white shadow-md mb-2 flex items-center justify-center">
				<div class="text-center">
					<h4 class="mb-5">
						<span class="text-2xl font-bold">4.0</span>
						<span class="text-sm">/5.0</span>
					</h4>
					<div class="flex justify-between flex-col items-center">
						<div class="flex space-x-1">
							<img src="/images/rating-star.svg" alt=""/>
							<img src="/images/rating-star.svg" alt=""/>
							<img src="/images/rating-star.svg" alt=""/>
							<img src="/images/rating-star.svg" alt=""/>
							<img src="/images/rating-star-6.svg" alt=""/>
						</div>
						<p class="py-5 text-gray-500">
							Rated by 64 people
						</p>
					</div>
				</div>
			</div>
			<div class="w-[360px] h-[253px] p-2 bg-white shadow-md">
				<h4 class="text-gray-500">Add comments</h4>
				<textarea rows="5" class="w-full p-2 border border-gray-200">
					Type here
				</textarea>
				<button class="w-full border text-gray-500 border-gray-200 py-2 mt-3">Submit</button>
			</div>
		</div>
	</div>
</section>
<Accordion />

<section class="my-10 px-10 w-screen">
    <div class="flex flex-col text-left justify-start items-start">
      <span class="text-green-600 text-2xl font-bold">You Might Also Like</span>
      <h3 class="mt-2 text-lg font-semibold text-gray-400">
        Other Related Products.
      </h3>
    </div>


    <div class="grid lg:grid-cols-4 md:grid-cols-3 justify-items-center mt-10 text-center">
        <article class="feature group h-[344px] relative text-left p-3 bg-white shadow-md">
            <div class="relative h-[60%]">
                <img
                class="m-auto w-full h-full"
                src="/groceries/date.png"
                alt="E Farm"
                />
                <div class="bg-black absolute w-full h-14 bottom-0 flex items-center justify-center group-hover:opacity-70 text-lg opacity-0 text-white">
                    <button>Add To Cart</button>
                </div>
            </div>
            <div on:click={toggleLike} class="bg-white cursor-pointer absolute top-4 right-5 p-2 rounded-full opacity-0 group-hover:opacity-70">
                <svg bind:this={element} class="likes__icon">
                    <use href="/icons.svg#icon-heart-outlined"></use>
                </svg>
            </div>
            <img class="absolute top-0 -left-0" src="/percentage.png" alt="Percentage taken"/>
            <h3 class="">
                <h5 class="py-2 font-medium">0.1kg teaspoonful Almond Seed</h5>
                <h5 class="text-gray-600 font-extralight">A one-line sub-text should be...</h5>
            </h3>
            <div class="flex space-x-1 py-3">
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star-6.svg" alt=""/>
            </div>
            <span class="font-bold">
                <span>N400.00</span>
                <span>/kg</span>
                <span class="text-red-400 line-through ml-4">N550.00</span>
            </span>
        </article>
    </div>

</section>

<section class="my-10 px-10 w-screen">
    <div class="flex flex-col text-left justify-start items-start">
      <span class="text-green-600 text-2xl font-bold">Recently Viewed</span>
      <h3 class="mt-2 text-lg font-semibold text-gray-400">
        Recently Viewed Items.
      </h3>
    </div>


    <div class="grid lg:grid-cols-4 md:grid-cols-3 justify-items-center mt-10 text-center">
        <article class="feature group h-[344px] relative text-left p-3 bg-white shadow-md">
            <div class="relative h-[60%]">
                <img
                class="m-auto w-full h-full"
                src="/groceries/date.png"
                alt="E Farm"
                />
                <div class="bg-black absolute w-full h-14 bottom-0 flex items-center justify-center group-hover:opacity-70 text-lg opacity-0 text-white">
                    <button>Add To Cart</button>
                </div>
            </div>
            <div on:click={toggleLike} class="bg-white cursor-pointer absolute top-4 right-5 p-2 rounded-full opacity-0 group-hover:opacity-70">
                <svg bind:this={element} class="likes__icon">
                    <use href="/icons.svg#icon-heart-outlined"></use>
                </svg>
            </div>
            <img class="absolute top-0 -left-0" src="/percentage.png" alt="Percentage taken"/>
            <h3 class="">
                <h5 class="py-2 font-medium">0.1kg teaspoonful Almond Seed</h5>
                <h5 class="text-gray-600 font-extralight">A one-line sub-text should be...</h5>
            </h3>
            <div class="flex space-x-1 py-3">
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star.svg" alt=""/>
                <img src="/images/rating-star-6.svg" alt=""/>
            </div>
            <span class="font-bold">
                <span>N400.00</span>
                <span>/kg</span>
                <span class="text-red-400 line-through ml-4">N550.00</span>
            </span>
        </article>
    </div>

</section>

<style>
	.likes__icon {
        fill: #F59A83;
        height: 1.5rem;
        width: 1.5rem; 
    }
</style>
