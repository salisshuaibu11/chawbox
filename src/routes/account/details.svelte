<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import AccountSideNav from "../../components/AccountSideNav.svelte";
</script>

<section class="w-screen -mt-24">
    <div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
        <div>
            <a href="#">Home </a>/ 
            <a href="#">Account </a> / 
            <a href="#">Account Details </a>
        </div>
        <div class="flex justify-center items-center mt-12">
            <img class="absolute mx-auto" src="/icons/details.svg" alt="" />
        </div>
    </div>

    <div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
            <h5 class="font-bold text-2xl my-4">Account Details</h5>
            <form>
                <h3 class="font-normal text-gray-400 mb-8 text-xl">PERSONAL</h3>
                <div class="mb-4">
                    <label for="firstname" class="block font-bold mb-2 text-lg text-black">First Name</label>
                    <input type="text" name="firstname" id="firstname" placeholder="First Name" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mb-4">
                    <label for="lastname" class="block font-bold mb-2 text-lg text-black">Last Name</label>
                    <input type="text" name="lastname" id="lastname" placeholder="Last Name" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mb-4">
                    <label for="email" class="block font-bold mb-2 text-lg text-black">Email Address</label>
                    <input type="email" name="email" id="email" placeholder="Email address" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mb-4">
                    <label for="phone" class="block font-bold mb-2 text-lg text-black">Phone Number</label>
                    <div class="flex justify-start items-center border rounded-md border-gray-200">
                        <div class="flex bg-gray-200 p-4">
                            <img src="/ngn.svg" alt="NGN" class="mr-2 inline">
                            <b class="mr-2">+234</b>
                        </div>
                        <input type="text" name="phone" id="phone" placeholder="Phone Number" class="bg-white p-4 text-gray-600 outline-none block w-full"/>
                    </div>
                </div>
                <div class="mb-4">
                    <label for="address" class="block font-bold mb-2 text-lg text-black">Address</label>
                    <textarea rows="2" name="address" id="address" placeholder="Address" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"></textarea>
                </div>
                <h3 class="font-normal text-gray-400 mt-8 mb-8 text-xl">BILLING ADDRESS</h3>
                <div class="mb-4">
                    <label for="address" class="block font-bold mb-2 text-lg text-black">Address</label>
                    <textarea rows="2" name="address" id="address" placeholder="Billing Address" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"></textarea>
                </div>
                <h3 class="font-normal text-gray-400 mt-8 mb-8 text-xl">SHIPPING ADDRESS</h3>
                <div class="mb-4">
                    <label for="address" class="block font-bold mb-2 text-lg text-black">Address</label>
                    <textarea rows="2" name="address" id="address" placeholder="Shipping Address" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"></textarea>
                </div>
                <div class="mt-4 mb-4">
                    <button type="submit" class="bg-green-700 text-white text-xl text-center p-4">Save Changes</button>
                </div>
            </form>
		</section>
	</div>

</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
