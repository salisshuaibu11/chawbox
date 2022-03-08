<script>
    import Footer from "../lib/Footer.svelte";
    import Header from "../components/Header.svelte";
    
</script>

<Header />
<section>
    <div class="bg-green-50 relative w-screen min-h-[200px] px-4 py-8">
      <div>
          <a href="/">Home </a>/ 
          <a href="/account/services">Blog </a> / 
      </div>
      <div class="flex justify-center items-center mt-12">
          <img class="absolute mx-auto" src="/icons/notification.svg" alt="" />
      </div>
    </div>
  <div class="bg-white px-8">
    <div class="mx-auto py-12 px-4 max-w-7xl sm:px-6 lg:px-8 lg:py-24">
      <div class="space-y-12">
        <div class="space-y-5 sm:space-y-4 md:max-w-xl lg:max-w-3xl xl:max-w-none">
          <h2 class="text-3xl font-extrabold tracking-tight sm:text-4xl">Our Team</h2>
          <p class="text-xl text-gray-500">Odio nisi, lectus dis nulla. Ultrices maecenas vitae rutrum dolor ultricies donec risus sodales. Tempus quis et.</p>
        </div>
        <ul class="space-y-12 sm:grid sm:grid-cols-2 sm:gap-x-6 sm:gap-y-12 sm:space-y-0 lg:grid-cols-3 lg:gap-x-8">
          <li>
            <div class="space-y-4">
              <div class="aspect-w-3 aspect-h-2">
                <img class="object-cover shadow-lg rounded-lg" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=8&w=1024&h=1024&q=80" alt="">
              </div>

              <div class="space-y-2">
                <div class="text-lg leading-6 font-medium space-y-1">
                  <h3 class="text-slate-900">Online Auto Seller goes from Concept to Launch</h3>
                  <p class="text-slate-500">Accurate, robust, usable search is what makes all your customer data an asset rather than a hindrance – here’s how we have improved...</p>
                </div>
              </div>
            </div>
          </li>

          <!-- More people... -->
        </ul>
      </div>
    </div>
  </div>
</section>
<Footer />