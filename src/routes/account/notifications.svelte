<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import AccountSideNav from "../../components/AccountSideNav.svelte";
</script>

<section class="w-screen -mt-24">
    <div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
        <div>
            <a href="/">Home </a>/ 
            <a href="/account/services">Account </a> / 
            <a href="#">Notification </a>
        </div>
        <div class="flex justify-center items-center mt-12">
            <img class="absolute mx-auto" src="/icons/notification.svg" alt="" />
        </div>
    </div>

    <div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
            <h5 class="font-bold text-2xl my-4">Notifications</h5>
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
