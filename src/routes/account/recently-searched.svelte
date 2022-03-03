<script>
    import { Icon, Search, X } from "svelte-hero-icons";
	import RecentlyViewed from '../../components/Products.svelte';
	import AccountSideNav from '../../components/AccountSideNav.svelte';

    let arrays = new Array(4);
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
           {#each arrays as searched}
                <div class="w-full mb-4 flex justify-between items-center text-xl">
                    <div class="flex items-center space-x-2">
                        <Icon src="{Search}" class="h-6 w-6 text-slate-400"/>
                        <span class="text-md font-light">wisconsis cheers curds</span>
                    </div>
                    <Icon src="{X}" class="h-6 w-6 text-slate-400 cursor-pointer"/>
                </div>
           {/each}
                
            <button class="block w-full text-center mx-auto mt-8 bg-red-50 p-4">
                <img src="/icons/delete.svg" class="inline-block" alt="Delete Icon" />
                <span class="text-red-500">Clear all</span>
            </button>
		</section>
	</div>
</section>

<RecentlyViewed title="Recently Viewed" subTitle="Recently Viewed Items" />
