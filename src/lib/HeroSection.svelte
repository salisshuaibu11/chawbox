<script>
    // import * as Icons from "../components/Icons";
    import { 
        Icon, 
        Search, 
        ShoppingCart, 
        ShoppingBag,
    } from "svelte-hero-icons";
</script>

<section class="mt-3 h-full flex flex-col items-center justify-center">
    <div class="mt-5 flex flex-col">
        <div class="flex mt-5 flex-col lg:py-0 py-4">
            <div class="text-center">
                <img src="/logo-orange.png" alt="logo" class="mb-4 mx-auto text-center"/>
                <p class="text-gray-200 text-lg tracking-widest font-bold">Your secured haven to shop anything Groceries and Farm essentials</p>
            </div>
            <div class="flex lg:w-[60rem] mt-4 relative bg-white items-center rounded mb-4">
                <div class="flex justify-center p-4">
                  <span class="flex items-center whitespace-no-wrap text-gray-600"> 
                    <Icon src="{Search}" class="h-6 w-6"/>
                  </span>
                </div>
                <input
                  type="text"
                  class="leading-normal flex-1 border-0 h-10 px-3 relative self-center font-roboto text-xl outline-none"
                  placeholder="Search Grocery items, Farm essentials and Agricultural commodities"
                />
                <div class="flex -mr-px">
                  <span
                    class="flex items-center leading-normal bg-green-800 border-0 px-4 text-white py-[16px] whitespace-no-wrap"
                    >
                    <Icon src="{Search}" class="h-6 w-6"/>
                    </span>
                </div>
            </div>
            <ul class="flex flex-wrap items-center justify-around text-white font-bold">
                <li class="flex cursor-pointer group my-2 group items-center space-x-1">
                    <Icon src="{ShoppingCart}" class="group-hover:text-yellow-500 w-6 h-6"/>
                    <span class="group-hover:text-yellow-500">E-commerce</span>
                </li>
                <li class="flex cursor-pointer my-2 group items-center space-x-1">
                    <svg class="group-hover:text-yellow-500" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g clip-path="url(#clip0_561_5017)">
                        <path d="M5.401 8.49902H4.01" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M7.13898 3.60898L6.09598 2.56598" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M12.01 1.89102V0.499023" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M16.879 3.60898L17.922 2.56598" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M18.618 8.49902H20.01" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M22.765 15.331C22.8396 15.3752 22.9015 15.4381 22.9444 15.5135C22.9874 15.5889 23.01 15.6742 23.01 15.761V22.98C23.01 23.1126 22.9573 23.2398 22.8636 23.3335C22.7698 23.4273 22.6426 23.48 22.51 23.48H1.51001C1.3774 23.48 1.25022 23.4273 1.15646 23.3335C1.06269 23.2398 1.01001 23.1126 1.01001 22.98V15.758C1.00996 15.6719 1.03211 15.5873 1.07433 15.5123C1.11655 15.4374 1.1774 15.3745 1.25101 15.33C6.74301 12 17.271 12.059 22.765 15.331Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M6.87901 23.501L10.14 12.912" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M0.990026 22.487L8.67603 13.043" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M17.14 23.48L13.879 12.92" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M22.945 22.487L15.242 13.043" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M12.01 23.501V12.856" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M16.3 11.064C16.7536 10.304 16.9975 9.43729 17.0065 8.55229C17.0156 7.66728 16.7896 6.79573 16.3516 6.02665C15.9136 5.25758 15.2793 4.61855 14.5135 4.17484C13.7477 3.73113 12.8778 3.49864 11.9928 3.50112C11.1077 3.5036 10.2392 3.74095 9.4759 4.18895C8.7126 4.63694 8.0819 5.27951 7.64821 6.05102C7.21452 6.82253 6.99339 7.69534 7.0074 8.58028C7.02142 9.46522 7.27008 10.3306 7.72798 11.088" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </g>
                        <defs>
                        <clipPath id="clip0_561_5017">
                        <rect width="24" height="24" fill="currentColor" transform="matrix(-1 0 0 1 24 0)"/>
                        </clipPath>
                        </defs>
                    </svg>             
                    <span class="group-hover:text-yellow-500">E-Farm</span>
                </li>
                <li class="flex my-2 cursor-pointer group items-center space-x-1">
                    <svg class="group-hover:text-yellow-500" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <g clip-path="url(#clip0_561_5017)">
                        <path d="M5.401 8.49902H4.01" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M7.13898 3.60898L6.09598 2.56598" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M12.01 1.89102V0.499023" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M16.879 3.60898L17.922 2.56598" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M18.618 8.49902H20.01" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M22.765 15.331C22.8396 15.3752 22.9015 15.4381 22.9444 15.5135C22.9874 15.5889 23.01 15.6742 23.01 15.761V22.98C23.01 23.1126 22.9573 23.2398 22.8636 23.3335C22.7698 23.4273 22.6426 23.48 22.51 23.48H1.51001C1.3774 23.48 1.25022 23.4273 1.15646 23.3335C1.06269 23.2398 1.01001 23.1126 1.01001 22.98V15.758C1.00996 15.6719 1.03211 15.5873 1.07433 15.5123C1.11655 15.4374 1.1774 15.3745 1.25101 15.33C6.74301 12 17.271 12.059 22.765 15.331Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M6.87901 23.501L10.14 12.912" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M0.990026 22.487L8.67603 13.043" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M17.14 23.48L13.879 12.92" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M22.945 22.487L15.242 13.043" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M12.01 23.501V12.856" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M16.3 11.064C16.7536 10.304 16.9975 9.43729 17.0065 8.55229C17.0156 7.66728 16.7896 6.79573 16.3516 6.02665C15.9136 5.25758 15.2793 4.61855 14.5135 4.17484C13.7477 3.73113 12.8778 3.49864 11.9928 3.50112C11.1077 3.5036 10.2392 3.74095 9.4759 4.18895C8.7126 4.63694 8.0819 5.27951 7.64821 6.05102C7.21452 6.82253 6.99339 7.69534 7.0074 8.58028C7.02142 9.46522 7.27008 10.3306 7.72798 11.088" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </g>
                        <defs>
                        <clipPath id="clip0_561_5017">
                        <rect width="24" height="24" fill="currentColor" transform="matrix(-1 0 0 1 24 0)"/>
                        </clipPath>
                        </defs>
                        </svg>
                        
                    <span class="group-hover:text-yellow-500">Farm Essential</span>
                </li>
                <li class="flex cursor-pointer group my-2 group items-center space-x-1">
                    <Icon src="{ShoppingBag}" class="group-hover:text-yellow-500 w-6 h-6"/>
                    <span class="group-hover:text-yellow-500">E-commodity</span>
                </li>
            </ul>
        </div>

        <div class="lg:mt-[10rem] mt-7 grid grid-cols-1 lg:grid-cols-3 gap-3 sm:grid-cols-3">
            <div class="flex space-x-2">
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_134_1227)">
                    <path d="M31.2617 18.7333H15.4283" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M22.9283 26.2334H16.6783C16.3468 26.2334 16.0289 26.1017 15.7945 25.8672C15.56 25.6328 15.4283 25.3149 15.4283 24.9834V16.65C15.4283 16.3185 15.56 16.0006 15.7945 15.7661C16.0289 15.5317 16.3468 15.4 16.6783 15.4H30.0117C30.3432 15.4 30.6611 15.5317 30.8956 15.7661C31.13 16.0006 31.2617 16.3185 31.2617 16.65V22.9" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M29.595 21.2333H27.095" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M19.595 22.9H17.095" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M21.2616 21.2333H17.095" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M29.595 26.2333V31.2333" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M32.095 28.7333H27.095" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M30.0416 34.4808L30.5025 34.3058C32.6941 33.4725 34.595 31.3692 34.595 29.0242V26.1967C34.5952 26.0271 34.5459 25.8612 34.4531 25.7194C34.3602 25.5776 34.2279 25.466 34.0725 25.3983C32.6341 24.861 31.1129 24.579 29.5775 24.565C28.0536 24.578 26.544 24.8602 25.1183 25.3983C24.9628 25.4659 24.8303 25.5775 24.7374 25.7193C24.6444 25.8612 24.5949 26.0271 24.595 26.1967V29.0242C24.595 31.3692 26.46 33.4708 28.6516 34.3058L29.1125 34.4808C29.4117 34.595 29.7424 34.595 30.0416 34.4808V34.4808Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    </g>
                    <circle cx="25" cy="25" r="25" fill="white" fill-opacity="0.2"/>
                    <defs>
                    <clipPath id="clip0_134_1227">
                    <rect width="20" height="20" fill="white" transform="translate(15 15)"/>
                    </clipPath>
                    </defs>
                </svg> 
                <h3 class="text-white font-semibold">
                    <span class="block">Secure Payment</span>
                    <span class="block">100% Secure Payment</span>
                </h3>      
            </div>

            <div class="flex space-x-2">
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_134_1234)">
                    <path d="M29 34.5H30C31.934 34.5 33.5 33.433 33.5 31.5V29.33" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M32.5 21.5C33.444 21.4993 34.3579 21.8326 35.0799 22.4408C35.8019 23.049 36.2855 23.8929 36.4452 24.8233C36.6049 25.7537 36.4304 26.7107 35.9525 27.5248C35.4746 28.3389 34.7242 28.9578 33.834 29.272C33.6832 29.3254 33.5218 29.3419 33.3633 29.32C33.2048 29.2982 33.0539 29.2386 32.9232 29.1463C32.7925 29.054 32.6858 28.9317 32.6122 28.7897C32.5386 28.6476 32.5001 28.49 32.5 28.33V21.5Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M17.5 21.5C16.5559 21.4993 15.6421 21.8326 14.9201 22.4408C14.1981 23.049 13.7145 23.8929 13.5548 24.8233C13.3951 25.7537 13.5696 26.7107 14.0475 27.5248C14.5253 28.3389 15.2758 28.9578 16.166 29.272C16.3168 29.3254 16.4782 29.3419 16.6367 29.32C16.7952 29.2982 16.9461 29.2386 17.0768 29.1463C17.2075 29.054 17.3141 28.9317 17.3878 28.7897C17.4614 28.6476 17.4999 28.49 17.5 28.33V21.5Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M32.5 23V21C32.5 19.0109 31.7098 17.1032 30.3033 15.6967C28.8968 14.2902 26.9891 13.5 25 13.5C23.0109 13.5 21.1032 14.2902 19.6967 15.6967C18.2902 17.1032 17.5 19.0109 17.5 21V23" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M24.5 33.5H28.5C28.6326 33.5 28.7598 33.5527 28.8536 33.6464C28.9473 33.7402 29 33.8674 29 34V35C29 35.1326 28.9473 35.2598 28.8536 35.3536C28.7598 35.4473 28.6326 35.5 28.5 35.5H24.5C24.2348 35.5 23.9804 35.3946 23.7929 35.2071C23.6054 35.0196 23.5 34.7652 23.5 34.5C23.5 34.2348 23.6054 33.9804 23.7929 33.7929C23.9804 33.6054 24.2348 33.5 24.5 33.5V33.5Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    </g>
                    <circle cx="25" cy="25" r="25" fill="white" fill-opacity="0.2"/>
                    <defs>
                    <clipPath id="clip0_134_1234">
                    <rect width="24" height="24" fill="white" transform="translate(13 13)"/>
                    </clipPath>
                    </defs>
                </svg>   
                <h3 class="text-white font-semibold">
                    <span class="block">24/7 Support</span>
                    <span class="block">Dedicated Support</span>
                </h3>      
            </div>

            <div class="flex space-x-2">
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="25" cy="25" r="25" fill="white" fill-opacity="0.2"/>
                    <path d="M23.125 27.5H18.125C17.7935 27.5 17.4755 27.3683 17.2411 27.1339C17.0067 26.8995 16.875 26.5815 16.875 26.25V25C16.875 24.6685 17.0067 24.3505 17.2411 24.1161C17.4755 23.8817 17.7935 23.75 18.125 23.75H31.875C32.2065 23.75 32.5245 23.8817 32.7589 24.1161C32.9933 24.3505 33.125 24.6685 33.125 25V26.25C33.125 26.5815 32.9933 26.8995 32.7589 27.1339C32.5245 27.3683 32.2065 27.5 31.875 27.5H26.875" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M26.875 27.5H31.25L30.7075 35.0887C30.685 35.4047 30.5435 35.7002 30.3114 35.9158C30.0794 36.1314 29.7742 36.2508 29.4575 36.25H20.5387C20.222 36.2508 19.9168 36.1314 19.6848 35.9158C19.4528 35.7002 19.3112 35.4047 19.2888 35.0887L18.75 27.5H23.125" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M23.125 23.75V36.25" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M26.875 36.25V23.75" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M20.625 22.11C21.375 22.865 25 23.75 25 23.75C25 23.75 24.1137 20.125 23.36 19.375C22.9973 19.0123 22.5054 18.8086 21.9925 18.8086C21.4796 18.8086 20.9877 19.0123 20.625 19.375C20.2623 19.7377 20.0586 20.2296 20.0586 20.7425C20.0586 21.2554 20.2623 21.7473 20.625 22.11V22.11Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M29.375 22.11C28.625 22.865 25 23.75 25 23.75C25 23.75 25.8863 20.125 26.64 19.375C26.8196 19.1954 27.0328 19.053 27.2674 18.9558C27.5021 18.8586 27.7535 18.8086 28.0075 18.8086C28.2615 18.8086 28.5129 18.8586 28.7476 18.9558C28.9822 19.053 29.1954 19.1954 29.375 19.375C29.5546 19.5546 29.697 19.7678 29.7942 20.0024C29.8914 20.2371 29.9414 20.4886 29.9414 20.7425C29.9414 20.9965 29.8914 21.248 29.7942 21.4826C29.697 21.7173 29.5546 21.9304 29.375 22.11V22.11Z" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M25 15.625V13.75" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M33.8387 19.2862L35.165 17.9612" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M37.5 27.5H39.375" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M16.1613 19.2862L14.835 17.9612" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M12.5 27.5H10.625" stroke="white" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
    
                <h3 class="text-white font-semibold">
                    <span class="block">Gift Service</span>
                    <span class="block">Dedicated Support</span>
                </h3>      
            </div>
        </div>
    </div>
</section>