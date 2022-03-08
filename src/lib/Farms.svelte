<script>
	import { Icon, Clock, CurrencyDollar } from 'svelte-hero-icons';
</script>

<section class="w-screen bg-orange-100">
	<div class="w-full py-24 px-8 sm:px-16 md:px-36 xl:px-48 mx-auto">
		<div class="text-center mb-16">
			<h1 class="text-green-800 text-4xl font-black">E-Farms</h1>
			<h5 class="mt-2 text-xl font-normal text-gray-600 tracking-wider">
				Here’s where Chaw members are having the most luck right now. Along with deals, discover
				trending picks.
			</h5>
		</div>

		<div
			class="grid grid-cols-2 lg:grid-cols-4 md:grid-cols-3 place-content-center gap-6 mt-10 text-center"
		>
			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/PoultryFarm.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				<p class="text-lg font-normal text-gray-600 pt-4">Poultry Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/RiceFarm.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				<p class="text-lg font-normal text-gray-600 pt-4">Rice Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/MaizeFarm.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Maize Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/PotatoFarm.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Potato Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/groundnut.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Groundnut Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/cashew.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Rice Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/poultry1.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Rice Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>

			<article
				class="feature group cursor-pointer relative h-fit text-left p-3 bg-white shadow-md overflow-hidden"
			>
				<div class="relative">
					<a href="/products/1234">
						<img class="m-auto w-full" src="/images/farms/poultry2.png" alt="Poultry Farm" /></a
					>
					<div
						class="absolute group-hover:bg-opacity-60 z-10 group-hover:opacity-100 bg-black w-full bg-opacity-0 flex top-0 py-[5rem] flex-col items-center transition-all  opacity-0 text-white space-y-2"
					>
						<div class="flex items-center space-x-1">
							<Icon src={CurrencyDollar} class="h-6 w-6" />
							<p>Apply 50%</p>
						</div>
						<div class="flex items-center space-x-2">
							<Icon src={Clock} class="h-6 w-6" />
							<p>6 months</p>
						</div>
					</div>
					<div class="flex space-x-2 bg-green-50 w-2/3 py-2 px-1 absolute bottom-0">
						<svg
							width="20"
							height="20"
							viewBox="0 0 14 14"
							fill="none"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								d="M11.0833 5.24996C11.0833 7.50513 6.99996 11.0833 6.99996 11.0833C6.99996 11.0833 2.91663 7.50513 2.91663 5.24996C2.91663 4.16699 3.34683 3.12838 4.11261 2.36261C4.87838 1.59683 5.91699 1.16663 6.99996 1.16663C8.08293 1.16663 9.12154 1.59683 9.88731 2.36261C10.6531 3.12838 11.0833 4.16699 11.0833 5.24996Z"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M2.33337 12.8334H11.6667"
								stroke="black"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
						<span class="text-sm">Kaduna, Branch</span>
					</div>
				</div>
				
				<p class="text-lg font-normal text-gray-600 pt-4">Rice Farm</p>
				<div>
					<span class="font-semibold text-xl text-gray-800">$150.00</span><span class="text-lg font-normal text-gray-600">/slot</span>
				</div>
			</article>
		</div>
		<div class="flex cursor-pointer mt-16">
			<div class="flex items-center justify-center w-full space-x-5">
				<h4 class="text-xl uppercase font-black">Explore All</h4>
				<svg
					class="slide-bck-left"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<g clip-path="url(#clip0_561_5121)">
						<path
							d="M18.5 7.49695L23.5 12.4969L18.5 17.4969"
							stroke="#031009"
							stroke-width="1.5"
							stroke-linecap="round"
							stroke-linejoin="round"
						/>
						<path
							d="M23.5 12.4969H0.5"
							stroke="#031009"
							stroke-width="1.5"
							stroke-linecap="round"
							stroke-linejoin="round"
						/>
					</g>
					<defs>
						<clipPath id="clip0_561_5121">
							<rect width="24" height="24" fill="white" />
						</clipPath>
					</defs>
				</svg>
			</div>
		</div>
	</div>
</section>

<style>
	@media only screen and (min-width: 969px) {
		section {
			clip-path: polygon(0 0, 100% 0, 100% 180vh, 0 100%);
		}
	}
</style>
