<script>
	import { onMount } from 'svelte';

	let prevArrow = `
    <svg class="slide-arrow z-20 prev-arrow h-24 w-24 absolute top-[6rem] left-0" viewBox="0 0 88 120" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g filter="url(#filter0_d_134_1441)">
        <circle cx="28" cy="60" r="28" fill="white"/>
        </g>
        <g clip-path="url(#clip0_134_1441)">
        <path d="M30.8333 67.5L23.6867 60.3533C23.6402 60.307 23.6034 60.2519 23.5782 60.1913C23.5531 60.1306 23.5402 60.0656 23.5402 60C23.5402 59.9344 23.5531 59.8694 23.5782 59.8087C23.6034 59.7481 23.6402 59.693 23.6867 59.6467L30.8333 52.5" stroke="black" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        </g>
        <defs>
        <filter id="filter0_d_134_1441" x="-32" y="0" width="120" height="120" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
        <feOffset/>
        <feGaussianBlur stdDeviation="16"/>
        <feComposite in2="hardAlpha" operator="out"/>
        <feColorMatrix type="matrix" values="0 0 0 0 0.891667 0 0 0 0 0.891667 0 0 0 0 0.891667 0 0 0 1 0"/>
        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_134_1441"/>
        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_134_1441" result="shape"/>
        </filter>
        <clipPath id="clip0_134_1441">
        <rect width="16" height="16" fill="white" transform="translate(20 52)"/>
        </clipPath>
        </defs>
    </svg>
    `;
	let nextArrow = `
    <svg class="slide-arrow next-arrow h-24 bottom-[7rem] right-0 w-24 absolute" viewBox="0 0 88 120" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g filter="url(#filter0_d_134_1444)">
        <circle r="28" transform="matrix(-1 0 0 1 60 60)" fill="white"/>
        </g>
        <g clip-path="url(#clip0_134_1444)">
        <path d="M57.1667 67.5L64.3133 60.3533C64.3598 60.307 64.3966 60.2519 64.4218 60.1913C64.4469 60.1306 64.4598 60.0656 64.4598 60C64.4598 59.9344 64.4469 59.8694 64.4218 59.8087C64.3966 59.7481 64.3598 59.693 64.3133 59.6467L57.1667 52.5" stroke="black" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        </g>
        <defs>
        <filter id="filter0_d_134_1444" x="0" y="0" width="120" height="120" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
        <feFlood flood-opacity="0" result="BackgroundImageFix"/>
        <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
        <feOffset/>
        <feGaussianBlur stdDeviation="16"/>
        <feComposite in2="hardAlpha" operator="out"/>
        <feColorMatrix type="matrix" values="0 0 0 0 0.891667 0 0 0 0 0.891667 0 0 0 0 0.891667 0 0 0 1 0"/>
        <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_134_1444"/>
        <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_134_1444" result="shape"/>
        </filter>
        <clipPath id="clip0_134_1444">
        <rect width="16" height="16" fill="white" transform="matrix(-1 0 0 1 68 52)"/>
        </clipPath>
        </defs>
    </svg>
    `;

	onMount(() => {
		window.$('.testimonials').slick({
			infinite: true,
			autoplay: true,
			speed: 300,
			slidesToShow: 3,
			prevArrow: prevArrow,
			nextArrow: nextArrow,
			slidesToScroll: 1,
			responsive: [
				{
					breakpoint: 1024,
					settings: {
						slidesToShow: 1,
						slidesToScroll: 1,
						infinite: true,
						dots: true
					}
				},
				{
					breakpoint: 600,
					settings: {
						slidesToShow: 1,
						slidesToScroll: 1
					}
				},
				{
					breakpoint: 480,
					settings: {
						slidesToShow: 1,
						slidesToScroll: 1
					}
				}
				// You can unslick at a given breakpoint now by adding:
				// settings: "unslick"
				// instead of a settings object
			]
		});
	});
</script>

<section class="w-screen bg-green-50">
	<div class="w-full py-24 px-8 sm:px-16 md:px-36 xl:px-48 mx-auto">
		<div class="text-center mb-16">
			<h1 class="text-green-800 text-4xl font-black">Customers’ Reviews</h1>
			<h5 class="mt-2 text-xl font-normal text-gray-600 tracking-wider">
				Here’s where Chaw members are saying about us.
			</h5>
		</div>

		<div class="testimonials relative w-full">
			<article class="text-left bg-white shadow-lg px-8 py-5 rounded-md">
				<div class="flex space-x-1 py-3">
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star-6.svg" alt="" />
				</div>
				<p class="pt-5 pb-10 text-slate-600 text-lg">
					“I just wanted to say thank you. Thanks for all the pretty support you give during these
					issues in the support que forum.”
				</p>
				<div class="flex space-x-2">
                    <div class="w-10 h-10">
					    <img src="/images/reviews/user1.png" class="w-full h-full" alt="" />
                    </div>
					<h3 class="">
						<span class="block font-semibold text-gray-700">Kemi Ororyo</span>
						<em class="block font-normal text-gray-500">E-commerce</em>
					</h3>
				</div>
			</article>

            <article class="text-left bg-white shadow-lg px-8 py-5 rounded-md">
				<div class="flex space-x-1 py-3">
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star-6.svg" alt="" />
				</div>
				<p class="pt-5 pb-10 text-slate-600 text-lg">
					“I just wanted to say thank you. Thanks for all the pretty support you give during these
					issues in the support que forum.”
				</p>
				<div class="flex space-x-2">
                    <div class="w-10 h-10">
					    <img src="/images/reviews/user1.png" class="w-full h-full" alt="" />
                    </div>
					<h3 class="">
						<span class="block font-semibold text-gray-700">Kemi Ororyo</span>
						<em class="block font-normal text-gray-500">E-commerce</em>
					</h3>
				</div>
			</article>

            <article class="text-left bg-white shadow-lg px-8 py-5 rounded-md">
				<div class="flex space-x-1 py-3">
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star-6.svg" alt="" />
				</div>
				<p class="pt-5 pb-10 text-slate-600 text-lg">
					“I just wanted to say thank you. Thanks for all the pretty support you give during these
					issues in the support que forum.”
				</p>
				<div class="flex space-x-2">
                    <div class="w-10 h-10">
					    <img src="/images/reviews/user1.png" class="w-full h-full" alt="" />
                    </div>
					<h3 class="">
						<span class="block font-semibold text-gray-700">Kemi Ororyo</span>
						<em class="block font-normal text-gray-500">E-commerce</em>
					</h3>
				</div>
			</article>

            <article class="text-left bg-white shadow-lg px-8 py-5 rounded-md">
				<div class="flex space-x-1 py-3">
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star.svg" alt="" />
					<img src="/images/rating-star-6.svg" alt="" />
				</div>
				<p class="pt-5 pb-10 text-slate-600 text-lg">
					“I just wanted to say thank you. Thanks for all the pretty support you give during these
					issues in the support que forum.”
				</p>
				<div class="flex space-x-2">
                    <div class="w-10 h-10">
					    <img src="/images/reviews/user1.png" class="w-full h-full" alt="" />
                    </div>
					<h3 class="">
						<span class="block font-semibold text-gray-700">Kemi Ororyo</span>
						<em class="block font-normal text-gray-500">E-commerce</em>
					</h3>
				</div>
			</article>

		</div>
	</div>
</section>
