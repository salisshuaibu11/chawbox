<script>
	import { onMount } from 'svelte';
	let btn;
	let menu;

	onMount(() => {
		btn.addEventListener('click', () => {
			menu.classList.toggle('hidden');
		});
	});
</script>

<nav>
	<div class="w-full py-4 px-8 sm:px-16 md:px-36 xl:px-48 mx-auto">
		<div class="flex justify-between">
			<div class="flex justify-start items-center">
				<div class="hidden md:flex items-center">
					<a
						href="/settings/about"
						class="px-2 lg:px-4 text-white text-sm lg:text-xl font-normal hover:text-white transition duration-300"
						>About Us</a
					>
					<a
						href="/account/services"
						class="px-2 lg:px-4 text-white text-sm lg:text-xl font-normal hover:text-white transition duration-300"
						>Our Services</a
					>
					<a
						href="/blog"
						class="px-2 lg:px-4 text-white text-sm lg:text-xl font-normal hover:text-white transition duration-300"
						>Blog</a
					>
					<a
						href="/contact"
						class="px-2 lg:px-4 text-white text-sm lg:text-xl font-normal hover:text-white transition duration-300"
						>Contact</a
					>
				</div>
			</div>
			<!-- Secondary Navbar items -->
			<div class="hidden md:flex justify-end items-center ">
				<a href="">
					<span class="px-4 lg:px-8 font-normal text-sm lg:text-xl text-white hover:text-white transition duration-300"
						>Log In</span
					></a
				>
				<a href="">
					<span
						class="px-4 lg:px-8 font-normal py-2 text-center text-sm lg:text-xl text-white hover:bg-white border-2 hover:text-green-800 rounded-md"
						>Register</span
					></a
				>
			</div>
			<!-- Mobile menu button -->
			<div class="md:hidden flex items-center">
				<button bind:this={btn} class="bg-green-800 p-4 rounded outline-none mobile-menu-button">
					<svg
						class=" w-8 h-8 text-gray-100"
						x-show="!showMenu"
						fill="none"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						viewBox="0 0 24 24"
						stroke="currentColor"
					>
						<path d="M4 6h16M4 12h16M4 18h16" />
					</svg>
				</button>
			</div>
		</div>
	</div>
</nav>

<!-- mobile menu -->
<div
	bind:this={menu}
	class="hidden md:hidden mobile-menu fixed bg-white top-0 left-0 z-50 w-1/2 min-h-screen p-8 my-0 mx-auto"
>
	<div class="">
		<ul class="text-center">
			<li class="active">
				<a href="index.html" class="block  text-sm px-2 py-4 text-green-800 font-semibold">Home</a>
			</li>
			<li>
				<a href="#services" class="block text-sm px-2 py-4 text-green-800 font-semibold"
					>Services</a
				>
			</li>
			<li>
				<a href="#about" class="block text-sm px-2 py-4 text-green-800 font-semibold"
					>About</a
				>
			</li>
			<li>
				<a href="#contact" class="block text-sm px-2 py-4 text-green-800 font-semibold"
					>Contact Us</a
				>
			</li>
			<li><br><hr><br></li>
			<li>
				<a href="" class="block py-2 px-2 text-green-800 font-semibold"
					>Log In</a
				>
			</li>
			<li>
				<a
					href=""
					class="block py-2 px-2 text-white bg-green-800 border"
					>Sign Up</a
				>
			</li>
		</ul>
	</div>
</div>

<style>
	a {
		position: relative;
		text-decoration: none;
		padding-bottom: 10px;
	}
	a::before {
		content: '';
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
