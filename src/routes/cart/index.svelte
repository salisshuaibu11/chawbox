<script>

    import FeaturedProducts from "../../components/Products.svelte";

    function decrement(e) {
		const btn = e.target.parentNode.parentElement.querySelector(
		'button[data-action="decrement"]'
		);
		const target = btn.nextElementSibling;
		let value = Number(target.value);
		value--;
		target.value = value;
  	}

	function increment(e) {
		const btn = e.target.parentNode.parentElement.querySelector(
		'button[data-action="decrement"]'
		);
		const target = btn.nextElementSibling;
		let value = Number(target.value);
		value++;
		target.value = value;
	}
</script>

<section class="w-screen p-10">
	<h2 class="text-2xl pb-4">Cart(8)</h2>
	<div class="w-full flex space-x-3">
		<section class="flex-1 space-y-2">
            <div class="w-full text-left bg-white p-3 rounded-md shadow-md flex space-x-3 items-center">
                <input type="checkbox" class="border w-4 h-4 border-gray-50"/>
                <h5>Select all items(8)</h5>
            </div>
			<article class="w-full bg-white shadow-md text-left py-5 px-3 flex space-x-2 rounded-md">
				<input type="checkbox" class="border w-4 h-4 border-gray-50"/>
                <div class="flex space-x-2 items-center">
                    <div class="w-[169px] h-full">
                        <img class="w-full h-full rounded-md" src="/groceries.png" alt=""/>
                    </div>
                    <div>
                        <p class="text-md font-bold">0.84kg Freshly Cut Sushi Vegetable In Stew</p>
                        <p class="text-gray-500 font-light">Extra texts comes here just a little but spans well coz it’s dsk.</p>
                        <h4 class="py-3">
                            <span class="text-xl font-bold">N350.00</span>
                            <span class="text-sm">/kg</span>
                        </h4>
                        <div class="w-full flex items-center justify-between">
                            <div class="custom-number-input border w-32">
                                <div class="flex flex-row w-full rounded-lg relative bg-transparent p-1">
                                  <button on:click={(e) => decrement(e)} data-action="decrement" class=" bg-gray-300 text-gray-600 hover:text-gray-700 hover:bg-gray-400 w-20 cursor-pointer outline-none">
                                    <span class="m-auto text-2xl font-thin">−</span>
                                  </button>
                                  <input type="number" class="outline-none focus:outline-none text-center w-full font-semibold text-md hover:text-black focus:text-black  md:text-basecursor-default flex items-center text-green-700" name="custom-input-number" value="0" />
                                    <button on:click={(e) => increment(e)} data-action="increment" class="bg-gray-300 text-gray-600 hover:text-gray-700 hover:bg-gray-400 w-20 cursor-pointer">
                                        <span class="m-auto text-2xl font-thin">+</span>
                                    </button>
                                </div>
                            </div>
                            <button class="flex items-center space-x-2">
                                <img src="/icons/delete.svg" alt="Delete Icon"/>
                                <span class="text-red-500">Delete</span>
                            </button>
                        </div>
                    </div>
                </div>
			</article>
		</section>
		<div class="w-[360px]">
			<div class="w-full bg-white rouned-lg py-2 shadow-md mb-2">
				<div class="p-2">
                    <h3 class="text-lg pb-2">Summary</h3>
                    <hr class="h-1 bg-gray-50"/>
                </div>
                <section class="flex p-2 justify-between pt-2">
                    <div>
                        <p>Sub-total</p>
                        <p class="text-gray-500 font-light">Shipping</p>
                        <p>Sub-Total</p>
                    </div>
                    <div>
                        <p>N510,000.00</p>
                        <p class="text-gray-500 font-light">Free</p>
                        <p>N510,000.00</p>
                    </div>
                </section>
                <section class="pt-3 px-2">
                    <div class="form-group px-2 bg-gray-100 py-4 rounded-md">
                        <label for="coupon" class="font-medium text-lg">Coupon/Promo Code</label>
                        <input type="text" class="border w-full my-2 border-gray-50 p-2" name="coupon" id="coupon" placeholder="Enter coupon code" />
                        <button class="text-center w-full border bg-slate-200 text-gray-700 border-gray-300 py-2 p-2">Apply Coupon</button>
                    </div>
                    <form class="py-4">
                        <div class="flex justify-between items-center">
                            <h4>Total</h4>
                            <h3 class="text-lg font-bold">N510,000.00</h3>
                        </div>
                        <button class="w-full p-3 my-5 text-center text-white bg-green-700">
                            Proceed to Checkout
                        </button>
                        <button class="border border-gray-200 w-full py-2 px-3">
                            Continue Shopping
                        </button>
                    </form>
                </section>
			</div>
		</div>
	</div>
</section>

<FeaturedProducts title="Recently Viewed" subTitle="Recently viewed items" />