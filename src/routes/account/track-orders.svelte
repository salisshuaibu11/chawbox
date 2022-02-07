<script>
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';
</script>

<section class="w-screen -mt-24">
	<div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
		<div>
			<a href="#">Home </a>/
			<a href="#">Account </a> /
			<a href="#">Track Orders </a>
		</div>
		<div class="flex justify-center items-center mt-12">
			<img class="absolute mx-auto" src="/icons/track-orders.svg" alt="" />
		</div>
	</div>

	<div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
			<h5 class="font-bold text-2xl my-4">Track Orders</h5>

                <div class="my-4 bg-white rounded border border-gray-200 shadow place-content-evenly p-2 grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="text-lg font-normal text-yellow-400">
                        <i class="fa fa-clock mr-3"></i> Ongoing
                    </div>
                    <div class="text-lg font-normal text-gray-300">
                        <i class="fa fa-check-circle mr-3"></i> Completed
                    </div>
                    <div class="text-lg font-normal text-gray-300">
                        <i class="fa fa-times-circle mr-3"></i> Pending
                    </div>
                </div>

                <article class=" mt-6 bg-white shadow border border-gray-200 p-4 rounded-md">
                    <div class="flex justify-start items-center">
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
                            <div class="flex space-x-1 mt-4">
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star-6.svg" alt="" />
                            </div>
                            <div class="mt-4">
                                <div>
                                    <span class="text-xl font-bold">N350.00</span>
                                    <span class="text-sm">/kg</span>
                                    <span class="ml-3 rounded bg-red-100 text-red-400 font-bold text-xl"
                                        ><s>N550.00</s></span
                                    >
                                </div>
                            </div>
                            <div class="mt-4 flex justify-between items-center">
                                <div>
                                    <span class="bg-orange-100 text-orange-400 rounded border text-lg border-orange-400 py-2 px-4">Pending</span>
                                </div>
                                <div class="flex justify-end">
                                    <button class="flex items-center justify-end">
                                        <span class="text-gray-600">See Details  &nbsp;<i class="fa fa-chevron-down"></i></span>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </article>

                <article class=" mt-6 bg-white shadow border border-gray-200 p-4 rounded-md">
                    <div class="flex justify-start items-center">
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
                            <div class="flex space-x-1 mt-4">
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star.svg" alt="" />
                                <img src="/images/rating-star-6.svg" alt="" />
                            </div>
                            <div class="mt-4">
                                <div>
                                    <span class="text-xl font-bold">N350.00</span>
                                    <span class="text-sm">/kg</span>
                                    <span class="ml-3 rounded bg-red-100 text-red-400 font-bold text-xl"
                                        ><s>N550.00</s></span
                                    >
                                </div>
                            </div>
                            <div class="mt-4 flex justify-between items-center">
                                <div>
                                    <span class="bg-orange-100 text-orange-400 rounded border text-lg border-orange-400 py-2 px-4">Pending</span>
                                </div>
                                <div class="flex justify-end">
                                    <button class="flex items-center justify-end">
                                        <span class="text-gray-600">See Details  &nbsp;<i class="fa fa-chevron-up"></i></span>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-4">
                        <div class="flex justify-start items-center">
                            <div class="bg-green-50 border border-green-900 rounded-full w-8 h-8 mr-2">
                                <i class="fa fa-check text-green-900 text-center mx-auto block pt-2"></i>
                            </div>
                            <span class="text-green-700 font-bold text-lg">Pending Confirmation</span>
                        </div>
                        <div class="bg-green-900 ml-3 h-5 w-0.5 block"></div>
                        <div class="flex justify-start items-center">
                            <div class="bg-green-50 border border-green-900 rounded-full w-8 h-8 mr-2">
                                <i class="fa fa-check text-green-900 text-center mx-auto block pt-2"></i>
                            </div>
                            <span class="text-green-700 font-bold text-lg">Confirmed</span>
                        </div>
                        <div class="bg-green-900 ml-3 h-5 w-0.5 block"></div>
                        <div class="flex justify-start items-center">
                            <div class="bg-green-50 border border-green-900 rounded-full w-8 h-8 mr-2">
                                <i class="fa fa-check text-green-900 text-center mx-auto block pt-2"></i>
                            </div>
                            <span class="text-green-700 font-bold text-lg">Shipped</span>
                        </div>
                        <div class="bg-green-900 ml-3 h-5 w-0.5 block"></div>
                        <div class="flex justify-start items-center">
                            <div class="bg-gray-100 border border-gray-400 rounded-full w-8 h-8 mr-2">
                                <i class="fa fa-check text-gray-400 text-center mx-auto block pt-2"></i>
                            </div>
                            <span class="text-gray-400 font-bold text-lg">Out For Delivery</span>
                        </div>
                        <div class="bg-gray-400 ml-3 h-5 w-0.5 block"></div>
                        <div class="flex justify-start items-center">
                            <div class="bg-gray-100 border border-gray-400 rounded-full w-8 h-8 mr-2">
                                <i class="fa fa-check text-gray-400 text-center mx-auto block pt-2"></i>
                            </div>
                            <span class="text-gray-400 font-bold text-lg">Delivered</span>
                        </div>
                    </div>
                </article>
                
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
