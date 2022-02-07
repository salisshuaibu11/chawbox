<header class="mb-24 shadow-b-xl">
<nav class="bg-white shadow dark:bg-gray-800">
	<div class="container px-6 py-3 mx-auto">
		<div class="flex flex-col md:flex-row md:justify-between md:items-center">
			<div class="flex items-center justify-between">
				<div>
					<a
						class="text-2xl font-bold text-gray-800 transition-colors duration-200 transform dark:text-white lg:text-3xl hover:text-gray-700 dark:hover:text-gray-300"
						href="#"><img src="/logo.svg" alt="Logo"></a
					>
				</div>

				<!-- Search input on desktop screen -->
				<div class="hidden mx-10 md:flex relative w-9/12 border border-green-700 rounded-lg p-2">
					<span class="absolute inset-y-0 left-0 flex items-center pl-3">
						<svg class="w-5 h-5 text-gray-400" viewBox="0 0 24 24" fill="none">
							<path
								d="M21 21L15 15M17 10C17 13.866 13.866 17 10 17C6.13401 17 3 13.866 3 10C3 6.13401 6.13401 3 10 3C13.866 3 17 6.13401 17 10Z"
								stroke="currentColor"
								stroke-width="2"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
					</span>

					<input
						type="text"
						class="w-full py-2 pl-10 pr-4 text-gray-700 bg-white outline-none"
						placeholder="Search"
					/>
					<button type="submit" class="bg-green-700 text-white rounded-md px-4 py-1">
						<i class="fa fa-search"></i>
					</button>
				</div>

				<!-- Mobile menu button -->
				<div class="flex md:hidden">
					<button
						type="button"
						class="text-gray-500 dark:text-gray-200 hover:text-gray-600 dark:hover:text-gray-400 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400"
						aria-label="toggle menu"
					>
						<svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
							<path
								fill-rule="evenodd"
								d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
							/>
						</svg>
					</button>
				</div>
			</div>

			<!-- Mobile Menu open: "block", Menu closed: "hidden" -->
			<div class="items-center md:flex">
				<div class="flex flex-row mt-2 md:mt-0 md:mx-1">
					<a class="mx-auto px-4 text-center"
						href="#">
						<i class='far fa-2x fa-heart'></i><br>
						<span>Wishlist</span></a
					>
					<a class="mx-auto px-4 text-center"
						href="#">
						<i class='far fa-2x fa-user'></i><br>
						<span>Account</span></a
					>
					<a class="mx-auto px-4 text-center"
						href="#"> 
						<i class='fa fa-2x fa-shopping-cart'></i><br>
						<span>Cart</span></a
					>
				</div>

				<!-- Search input on mobile screen -->
				<div class="mt-3 md:hidden">
					<div class="relative flex">
						<span class="absolute inset-y-0 left-0 flex items-center pl-3">
							<svg class="w-5 h-5 text-gray-400" viewBox="0 0 24 24" fill="none">
								<path
									d="M21 21L15 15M17 10C17 13.866 13.866 17 10 17C6.13401 17 3 13.866 3 10C3 6.13401 6.13401 3 10 3C13.866 3 17 6.13401 17 10Z"
									stroke="currentColor"
									stroke-width="2"
									stroke-linecap="round"
									stroke-linejoin="round"
								/>
							</svg>
						</span>

						<input
							type="text"
							class="w-full py-2 pl-10 pr-4 text-gray-700 bg-white border rounded-md"
							placeholder="Search"
						/>
						<button type="submit" class="bg-green-700 text-white rounded-md px-4 mx-2 py-1">
							<i class="fa fa-search"></i>
						</button>
					</div>
				</div>
			</div>
		</div>

	</div>
</nav>

<div class="py-3 px-4 md:px-12 overflow-y-auto whitespace-nowrap scroll-hidden bg-orange-100 flex items-center justify-between">
	<div>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">About Us</a
		>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">Our Services</a
		>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">Blog</a
		>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">Contact Us</a
		>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">Shop</a
		>
	</div>
	<div class="flex justify-end items-center space-x-5">
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">Get App</a
		>
		<a
			class="mx-4 text-sm leading-5 text-gray-700 transition-colors duration-200 transform md:my-0"
			href="#">
			<img src="/ngn.svg" class="w-8 h-4 inline-block" alt="Naija" />
			&nbsp;
			NGN
			&nbsp; <i class="fa fa-chevron-down"></i></a
		>
	</div>
</div>

</header>
<!-- Require css -->
<style>
	.scroll-hidden::-webkit-scrollbar {
		height: 0px;
		background: transparent; /* make scrollbar transparent */
	}
</style>
