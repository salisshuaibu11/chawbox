<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import AccountSideNav from "../../components/AccountSideNav.svelte";
</script>

<section class="w-screen -mt-24">
    <div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
        <div>
            <a href="/">Home </a>/ 
            <a href="/account/services">Account </a> / 
            <a href="#">Services </a>
        </div>
        <div class="flex justify-center items-center mt-12">
            <img class="absolute mx-auto" src="/icons/services.svg" alt="" />
        </div>
    </div>

    <div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 my-5 h-fit mx-4 md:mx-8">
            <h5 class="font-bold text-lg">Services</h5>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-4 place-content-center mt-10 text-center mx-auto">
                <article class="text-left relative min-h-[300px] p-3 bg-white shadow-md border border-gray-200 rounded-lg">
                    <div class="flex items-center justify-between">
                        <span class="font-bold text-2xl my-6">E-Commerce</span>
                        <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span>
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 right-0" src="/icons/money.svg" alt="E-Commerce"/>
                </article>

                <article class="text-left relative min-h-[300px] p-3 bg-white shadow-md border border-gray-200 rounded-lg">
                    <div class="flex items-center justify-between">
                        <span class="font-bold text-2xl my-6">E-Farm</span>
                        <!-- <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span> -->
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 right-0" src="/icons/farming-field-sun.svg" alt="E-Commerce"/>
                </article>

                <article class="text-left relative min-h-[300px] p-3 bg-white shadow-md border border-gray-200 rounded-lg">
                    <div class="flex items-center justify-between">
                        <span class="font-bold text-2xl my-6">E-Commodity</span>
                        <!-- <span class="bg-green-100 border border-green-400 px-3 rounded-lg">Active</span> -->
                    </div>
                    <p class="text-gray-500 font-light py-5">
                        Information on this topic comes here, and should not be too lengthy.
                    </p>
                    <img class="absolute bottom-0 right-0" src="/icons/commodity.svg" alt="E-Commerce"/>
                </article>
            </div>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />