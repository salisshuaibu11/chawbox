<script>
    import Steps from "../../components/CheckoutSteps.svelte";
</script>

<section class="w-screen -mt-24">
    <div>
        <a href="/">Home </a>/ 
        <a href="/account/services">Account </a> / 
        <a href="#">Checkout </a>
    </div>

    <section class="w-screen bg-gray-50 py-10 px-5">
        <h2 class="text-2xl pb-4">Checkout</h2>
        <div class="w-full flex-column lg:flex space-x-3">
            <section class="flex-1 space-y-2">
                <Steps />
            </section>
            <div class="w-[25rem] h-fit bg-white shadow-md px-5 py-3">
                <dl class="font-semibold text-2xl">
                    <dt class="text-gray-900">Order Summary</dt>
                </dl>
        
                <ul class="mt-2 text-sm font-medium border-t border-gray-200 divide-y divide-gray-200">
                    
                    <li class="flex py-6 space-x-6">
                        <img src="/cooked.png" alt="Model wearing men&#039;s charcoal basic tee in large." class="flex-none w-24 h-24 bg-gray-100 rounded-md object-center object-cover">
                        <div>
                            <p class="text-lg font-semibold">Sushi-Made Vegetable</p>
                            <p class="my-3 text-gray-500">Mobile checkout page work, designs, illustrations, and graphic elements</p>
                            <div class="flex justify-between text-lg">
                                <h3>
                                    <span>N350</span>
                                    <span class="text-gray-500">/kg</span>
                                </h3>
                                <h3>
                                    <span>Qty:</span>
                                    <span>17x</span>
                                </h3>
                            </div>
                        </div>
                    </li>
        
                    <!-- More products... -->
                </ul>
        
                <dl class="text-sm font-medium space-y-6 border-t border-gray-200 pt-6">
                    <div class="flex justify-between text-gray-500 ">
                        <dt>Subtotal</dt>
                        <dd class="text-gray-900">N150,000.00</dd>
                    </div>
        
                    <div class="flex justify-between text-gray-500 ">
                        <dt>Shipping</dt>
                        <dd class="text-gray-900">Free</dd>
                    </div>
        
                    <div class="flex items-center font-semibold justify-between border-t border-gray-200 text-gray-900 pt-6">
                        <dt class="text-base">Total</dt>
                        <dd class="text-base">N51,000</dd>
                    </div>
                </dl>
            </div>
        </div>
    </section>

</section>
