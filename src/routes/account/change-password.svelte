<script>
    import RecentlyViewed from "../../components/Products.svelte";
    import AccountSideNav from "../../components/AccountSideNav.svelte";
</script>

<section class="w-screen -mt-24">
    <div class="bg-green-50 relative w-screen min-h-[250px] px-4 py-8">
        <div>
            <a href="#">Home </a>/ 
            <a href="#">Account </a> / 
            <a href="#">Change Password </a>
        </div>
        <div class="flex justify-center items-center mt-12">
            <img class="absolute mx-auto" src="/icons/change-password.svg" alt="" />
        </div>
    </div>

    <div class="w-full md:flex md:px-18 lg:px-24 xl:px-32">
		<AccountSideNav />
		<section class="flex-1 mx-4 md:mx-12 my-5 h-fit">
            <h5 class="font-bold text-2xl my-4">Change Password</h5>
            <form>
                <div class="mb-4">
                    <label for="password" class="block font-bold mb-2 text-lg text-black">Enter Existing Password</label>
                    <input type="password" name="password" id="password" placeholder="Enter Existing Password" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mb-4">
                    <label for="password" class="block font-bold mb-2 text-lg text-black">Enter New Password</label>
                    <input type="password" name="password" id="password" placeholder="Enter New Password" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mb-4">
                    <label for="password" class="block font-bold mb-2 text-lg text-black">Confirm New Password</label>
                    <input type="password" name="password" id="password" placeholder="Confirm New  Password" class="border rounded-md border-gray-200 p-4 text-gray-600 outline-none block w-full"/>
                </div>
                <div class="mt-4 mb-4">
                    <button type="submit" class="bg-green-700 text-white text-xl text-center p-4">Save Changes</button>
                </div>
            </form>
		</section>
	</div>

</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
