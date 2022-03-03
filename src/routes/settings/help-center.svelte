<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="#">Home </a>/
			<a href="#">Account </a> /
			<a href="#">Help Center</a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/help-center.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-4">Help Center</h5>

			<div class="my-4 bg-green-700 rounded p-2 flex space-x-2">
					<div class="text-lg font-normal text-white">
							<span>You can reach us via</span>
							<i class="fa fa-arrow-right mr-3"></i>
					</div>
					<div>
							<div class="text-lg font-normal text-white">
									<i class="fa fa-arrow-right mr-3"></i>
									<span>You can reach us via</span>
							</div>
					</div>
			</div>
        
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
