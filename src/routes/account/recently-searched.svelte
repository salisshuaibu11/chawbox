<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="/">Home </a>/
			<a href="/account/services">Account </a> /
			<a href="#">Recently Searched </a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/searched.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-8">Recently Searched</h5>

            <div class="block w-full mb-4 flex justify-between items-center text-xl text-gray-400">
                <div>
                    <i class="fa fa-search mr-2"></i>
                    <span>Lorem ipsum dolor sit amet, consectetur</span>
                </div>
                <div><i class="fa fa-times"></i></div>
            </div>
            <div class="block w-full mb-4 flex justify-between items-center text-xl text-gray-400">
                <div>
                    <i class="fa fa-search mr-2"></i>
                    <span>Lorem ipsum dolor sit amet, consectetur</span>
                </div>
                <div><i class="fa fa-times"></i></div>
            </div>
            <div class="block w-full mb-4 flex justify-between items-center text-xl text-gray-400">
                <div>
                    <i class="fa fa-search mr-2"></i>
                    <span>Lorem ipsum dolor sit amet, consectetur</span>
                </div>
                <div><i class="fa fa-times"></i></div>
            </div>
            <div class="block w-full mb-4 flex justify-between items-center text-xl text-gray-400">
                <div>
                    <i class="fa fa-search mr-2"></i>
                    <span>Lorem ipsum dolor sit amet, consectetur</span>
                </div>
                <div><i class="fa fa-times"></i></div>
            </div>
            <div class="block w-full mb-4 flex justify-between items-center text-xl text-gray-400">
                <div>
                    <i class="fa fa-search mr-2"></i>
                    <span>Lorem ipsum dolor sit amet, consectetur</span>
                </div>
                <div><i class="fa fa-times"></i></div>
            </div>
                
            <button class="block w-full text-center mx-auto mt-8 bg-red-50 p-4">
                <img src="/icons/delete.svg" class="inline-block" alt="Delete Icon" />
                <span class="text-red-500">Delete</span>
            </button>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
