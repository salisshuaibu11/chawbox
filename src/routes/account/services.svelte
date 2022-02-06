<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import ProductSideNav from "../../components/ProductSideNav.svelte";
</script>

<section class="w-screen">
    <div class="bg-green-100 w-full h-44 relative px-28 py-5">
        <span>Home / Account / Services</span>
        <img class="absolute left-[39.25rem]" src="/icons/services.svg" alt="" />
    </div>

    <div class="w-full flex space-x-3 px-28">
		<ProductSideNav />
		<section class="flex-1 px-3 my-5 h-fit">
            <h5 class="font-bold text-lg">Services</h5>

            <div class="grid lg:grid-cols-3 gap-12 px-2 py-2 md:grid-cols-3 justify-items-center mt-10 text-center">
                <article class="text-left w-[264px] relative min-h-[290px] p-3 bg-white shadow-md">
                    <div class="flex items-center justify-between">
                        <span class="">E-Commerce</span>
                        <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span>
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 left-32" src="/icons/money.svg" alt="E-Commerce"/>
                </article>

                <article class="text-left w-[264px] relative min-h-[290px] p-3 bg-white shadow-md">
                    <div class="flex items-center justify-between">
                        <span class="">E-Farm</span>
                        <!-- <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span> -->
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 left-36" src="/icons/farming-field-sun.svg" alt="E-Commerce"/>
                </article>

                <article class="text-left w-[264px] relative min-h-[290px] p-3 bg-white shadow-md">
                    <div class="flex items-center justify-between">
                        <span class="">E-Commodity</span>
                        <!-- <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span> -->
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 left-40" src="/icons/commodity.svg" alt="E-Commerce"/>
                </article>
            </div>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />