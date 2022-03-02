<script>
    import { onMount } from "svelte";
    let btn;
    let menu;

    onMount(() => {
            btn.addEventListener("click", () => {
        menu.classList.toggle("hidden");
    });
    })
</script>

<nav>
    <div class="max-w-6xl mx-auto">
        <div class="flex justify-between">
            <div class="flex space-x-7">
                <div class="hidden md:flex items-center space-x-1">
                    <a href="/settings/about" class="py-4 px-2 text-white font-semibold">About Us</a>
                    <a href="/account/services" class="py-4 px-2 text-gray-100 font-semibold hover:text-white transition duration-300">Our Services</a>
                    <a href="/blog" class="py-4 px-2 text-gray-100 font-semibold hover:text-white transition duration-300">Blog</a>
                    <a href="/contact" class="py-4 px-2 text-gray-100 font-semibold hover:text-white transition duration-300">Contact</a>
                </div>
            </div>
            <!-- Secondary Navbar items -->
            <div class="hidden md:flex items-center space-x-3 ">
                <a href="" class="py-2 px-2 font-medium text-gray-100 hover:text-white transition duration-300">Log In</a>
                <a href="" class="py-2 px-2 font-medium text-white hover:bg-white hover:text-black border rounded transition duration-300">Sign Up</a>
            </div>
            <!-- Mobile menu button -->
            <div class="md:hidden flex items-center">
                <button bind:this={btn} class="outline-none mobile-menu-button">
                <svg class=" w-6 h-6 text-gray-100"
                    x-show="!showMenu"
                    fill="none"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                >
                    <path d="M4 6h16M4 12h16M4 18h16"></path>
                </svg>
            </button>
            </div>
        </div>
    </div>
    <!-- mobile menu -->
    <div bind:this={menu} class="hidden mobile-menu">
        <ul class="">
            <li class="active"><a href="index.html" class="block  text-sm px-2 py-4 text-gray-100 font-semibold">Home</a></li>
            <li><a href="#services" class="block text-sm px-2 py-4 text-gray-100 hover:text-white transition duration-300">Services</a></li>
            <li><a href="#about" class="block text-sm px-2 py-4 text-gray-100 hover:text-white transition duration-300">About</a></li>
            <li><a href="#contact" class="block text-sm px-2 py-4 text-gray-100 hover:text-white transition duration-300">Contact Us</a></li>
            <div class="flex items-center space-x-3 ">
                <a href="" class="py-2 px-2 font-medium text-gray-100 hover:text-white transition duration-300">Log In</a>
                <a href="" class="py-2 px-2 font-medium text-white hover:bg-white hover:text-black border rounded transition duration-300">Sign Up</a>
            </div>
        </ul>
    </div>
</nav>

<style>
a {
  position: relative;
  text-decoration: none;
  padding-bottom: 10px;
}
a::before {
  content: "";
  position: absolute;
  display: block;
  width: 100%;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #fff;
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

a:hover::before {
  transform: scaleX(1);
}
</style>