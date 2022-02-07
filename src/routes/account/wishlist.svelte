<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="#">Home </a>/
			<a href="#">Account </a> /
			<a href="#">Wishlist </a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/wishlist.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-4">Wishlist</h5>

				<div class="flex justify-start items-center mt-6 bg-white shadow border border-gray-200 p-4 rounded-md">
					<div class="h-full w-[200px] mr-4">
						<img class="w-auto h-max rounded-md" src="/groceries.png" alt="" />
					</div>
					<div>
						<div class="flex justify-between items-start">
							<div>
								<p class="text-md font-bold">0.84kg Freshly Cut Sushi Vegetable In Stew</p>
								<p class="text-gray-500 font-light">
									Extra texts comes here just a little but spans well coz it’s dsk.
								</p>
							</div>
							<div class="flex justify-end">
                                <div class="ml-4 w-10 h-10 rounded-full mx-auto flex justify-center border-2 border-gray-200">
                                    <i class="text-center fa fa-heart mx-auto block text-red-400 pt-3"></i>
                                </div>
                            </div>
						</div>
						<div class="mt-4 flex justify-between items-center">
							<div>
								<span class="text-xl font-bold">N350.00</span>
								<span class="text-sm">/kg</span>
								<span class="ml-3 rounded bg-red-100 text-red-400 font-bold text-xl"
									><s>N550.00</s></span
								>
							</div>
							<div class="flex justify-end">
								<button class="flex items-center justify-end">
									<img src="/icons/delete.svg" alt="Delete Icon" />
									<span class="text-red-500">Delete</span>
								</button>
							</div>
						</div>
					</div>
				</div>
                
                
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
