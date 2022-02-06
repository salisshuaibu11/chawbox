<script>
    import { page } from "$app/stores";

    const {pathname} = $page.url
</script>

<section class="space-y-2 w-[250px] relative -top-12 bg-white shadow-md rounded-md">
    <article class="w-full text-left cursor-pointer pt-4">
        <p class="uppercase text-xs text-gray-500 px-3 pb-4 font-light">general</p>
        <a href="/account/services" class="flex items-center space-x-2 px-3 py-2 border-r-2 border-green-600">
            <img class="w-4 h-4" src="/icons/services/services.svg" alt="" />
            <span class="text-green-500">Services</span>
        </a>
        <a href="/account/notifications" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/notification.svg" alt="Notification" />
            <span class="">Notifications</span>
        </a>
    </article>
    <article class="w-full text-left cursor-pointer pt-4">
        <p class="uppercase text-xs text-gray-500 px-3 pb-4 font-light">my account</p>
        <a href="/account/details" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/services.svg" alt="Account details icon" />
            <span class="font-thin">Account Details</span>
        </a>
        <a href="/account/wallet" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/wallet.svg" alt="Wallet Icon" />
            <span class="">Wallet</span>
        </a>
        <a href="/account/whishlist" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/whishlist.svg" alt="Whishlist Icon" />
            <span class="">Whishlist</span>
        </a>
        <a href="/account/trackorders" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/trackOrder.png" alt="Whishlist Icon" />
            <span class="">Track Orders</span>
        </a>
        <a href="/account/recentlyviewed" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/viewed.svg" alt="Whishlist Icon" />
            <span class="">Recently Viewed</span>
        </a>
        <a href="/account/searched" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/search.svg" alt="Whishlist Icon" />
            <span class="">Recently Searched</span>
        </a>
        <a href="/account/chagepassword" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/password.svg" alt="Whishlist Icon" />
            <span class="">Change Password</span>
        </a>
    </article>
    <article class="w-full text-left cursor-pointer pt-4">
        <p class="uppercase text-xs text-gray-500 px-3 pb-4 font-light">settings</p>
        <a href="/settings/shippingpolicy" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/shippingPolicy.svg" alt="Shipping Policy" />
            <span class="font-thin">Shipping Policy</span>
        </a>
        <a href="/settings/exchanges" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/earnings.svg" alt="Returns and Exchanges" />
            <span class="">Returns and Exchanges</span>
        </a>
        <a href="/settings/about" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/earnings.svg" alt="About Us" />
            <span class="">About Us</span>
        </a>
        <a href="/settings/helpcenter" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/services.svg" alt="Help Center" />
            <span class="">Help Center</span>
        </a>
        <a href="/settings/earn" class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/services/services.svg" alt="Refer and Earn" />
            <span class="">Refer and Earn</span>
        </a>
    </article>

    <article class="w-full text-left cursor-pointer pt-4">
        <div class="flex items-center space-x-2 px-3 py-2">
            <img class="w-4 h-4" src="/icons/logout.svg" alt="Shipping Policy" />
            <span class="font-thin text-red-400">Logout</span>
        </div>
    </article>
</section>
