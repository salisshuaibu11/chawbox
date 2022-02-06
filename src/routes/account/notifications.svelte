<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import ProductSideNav from "../../components/ProductSideNav.svelte";
</script>

<section class="w-screen">
    <div class="bg-green-100 w-full h-44 relative px-28 py-5">
        <span>Home / Account / Notification</span>
        <img class="absolute left-[39.25rem]" src="/icons/services.svg" alt="" />
    </div>

    <div class="w-full flex space-x-3 px-28">
		<ProductSideNav />
		<section class="flex-1 px-3 my-5 h-fit">
            <h5 class="font-bold text-lg">Notifications</h5>
            <article class="space-y-2">
                <div class="flex space-x-2 items-start bg-orange-50 px-3 pt-2 pb-6">
                    <div class="bg-white p-2 border border-gray-300 rounded-full">
                        <img src="/icons/alarm-bell.svg" alt="Alarm Bell"/>
                    </div>
                    <div class="font-light flex-1">
                        <h4 class="flex justify-between items-center space-y-2">
                            <span class="block text-green-500">support@chawbox.com</span>
                            <span class="text-gray-500 font-light">22 minutes ago</span>
                        </h4>
                        <span class="block">A feat is an exemplary, even bold achievement, often an act of great skill</span>
                    </div>      
                </div>
                <div class="flex space-x-2 items-start bg-orange-50 px-3 pt-2 pb-6">
                    <div class="bg-white p-2 border border-gray-300 rounded-full">
                        <img src="/icons/alarm-bell.svg" alt="Alarm Bell"/>
                    </div>
                    <div class="font-light flex-1">
                        <h4 class="flex justify-between items-center space-y-2">
                            <span class="block text-green-500">The Mayor of Casterbridge Cartel</span>
                            <span class="text-gray-500 font-light">22 minutes ago</span>
                        </h4>
                        <span class="block">A feat is an exemplary, even bold achievement, often an act of great skill</span>
                    </div> 
                </div>
                <div class="flex space-x-2 items-start bg-white px-3 pt-2 pb-6">
                    <div class="bg-orange-50 p-2 border border-gray-300 rounded-full">
                        <img src="/icons/alarm-bell.svg" alt="Alarm Bell"/>
                    </div>
                    <div class="font-light flex-1">
                        <h4 class="flex justify-between items-center space-y-2">
                            <span class="block text-green-500">Fanboy Connectives</span>
                            <span class="text-gray-500 font-light">22 minutes ago</span>
                        </h4>
                        <span class="block">A feat is an exemplary, even bold achievement, often an act of great skill</span>
                    </div> 
                </div>
            </article>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
