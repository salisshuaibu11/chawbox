<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="/">Home </a>/
			<a href="/account/services">Account </a> /
			<a href="/recently-viewed">Recently Viewed </a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/viewed.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-4">Recently Viewed</h5>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <article class="feature group relative text-left p-3 bg-white shadow-md">
                    <div class="relative h-auto">
                        <img
                        class="m-auto w-full h-full"
                        src="/groceries/date.png"
                        alt="E Farm"
                        />
                        <div class="bg-black absolute w-full h-10 bottom-0 flex items-center justify-center group-hover:opacity-70 text-lg opacity-0 text-white">
                            <button>Add To Cart</button>
                        </div>
                    </div>
                    <div class="bg-white cursor-pointer absolute top-4 right-5 p-2 rounded-full opacity-0 group-hover:opacity-70">
                        <svg class="likes__icon">
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
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
