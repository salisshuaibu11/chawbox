<section class="w-screen px-10">
  <ul class="nav nav-tabs flex flex-col mt-[5rem] bg-green-100 py-2 px-5 md:flex-row flex-wrap list-none border-b-0 pl-0 mb-4" id="tabs-tabFill"
  role="tablist">
    <li class="nav-item flex-auto text-center text-green-500 active" role="presentation">
      <a href="#tabs-description" class="" id="tabs-description" data-bs-toggle="pill" data-bs-target="#tabs-description" role="tab"
        aria-controls="tabs-description" aria-selected="true">Description</a>
    </li>
    <li class="nav-item flex-auto text-center text-green-500" role="presentation">
      <a href="#tabs-profileFill" class="" id="tabs-profile-tabFill" data-bs-toggle="pill" data-bs-target="#tabs-profileFill" role="tab"
        aria-controls="tabs-profileFill" aria-selected="false">How To Use</a>
    </li>
    <li class="nav-item flex-auto text-center text-green-500" role="presentation">
      <a href="#tabs-messagesFill" class="" id="tabs-messages-tabFill" data-bs-toggle="pill" data-bs-target="#tabs-messagesFill" role="tab"
        aria-controls="tabs-messagesFill" aria-selected="false">Packing Information</a>
    </li>
    <li class="nav-item flex-auto text-center text-green-500" role="presentation">
      <a href="#tabs-messagesFill" class="" id="tabs-messages-tabFill" data-bs-toggle="pill" data-bs-target="#tabs-messagesFill" role="tab"
        aria-controls="tabs-messagesFill" aria-selected="false">Additional Details</a>
    </li>
  </ul>
  <div class="tab-content" id="tabs-tabContentFill">
    <div class="tab-pane fade show active" id="tabs-description" role="tabpanel" aria-labelledby="tabs-description">
      <div class="flex lg:flex-row flex-col">
        <div class="flex-1 font-light">
          <p>Are you looking for a few great farm stories and books for kids? You’re in luck! Here are some of our favorite farm stories that we’re so excited to share with you!</p>
          <p class="py-5">Farms are so interesting for kids because they are full of animals, bright colors, animal noises, and mud! This list of farm stories for kids includes board books and picture books that celebrate all the fun of farm life. From adorable animals to friendly tractors, there are lots of cute characters in these books to get them excited about the farm.</p> 
          <p>Make certain to pair your reading fun of these farm stories up with fun farming learning, too. These Farm Animal Activities For Preschoolers will go perfectly with these books! We’re also a HUGE fan of this Farm Animals Printable Packet</p>
        </div>
        <div class="flex-1">
          <img class="wi-full" src="/groceries.png" alt="" />
        </div>
      </div>
      <div class="font-light mt-2 space-y-1">
        <p class="text-justify">
          Are you looking for a few great farm stories and books for kids? You’re in luck! Here are some of our favorite farm stories that we’re so excited to share with you!
          Farms are so interesting for kids because they are full of animals, bright colors, animal noises, and mud! This list of farm stories for kids includes board books and picture books that celebrate all the fun of farm life. From adorable animals to friendly tractors, there are lots of cute characters in these books to get them excited about the farm.
        </p>
        <p>Make certain to pair your reading fun of these farm stories up with fun farming learning, too. These Farm Animal Activities For Preschoolers will go perfectly with these books! We’re also a HUGE fan of this Farm Animals Printable Packet as well.</p>
      </div>
    </div>
  </div>
</section>

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
    height: 5px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    bottom: 0;
    left: 0;
    background-color: rgb(94, 230, 61);
    transform: scaleX(0);
    transition: transform 0.3s ease;
  }

  ul > li > .active {
    background-color: rgb(70, 228, 70);
    display: block;
    width: 100%;
    height: 2px;
    bottom: 0;
    left: 0;
    padding-bottom: 10px;
  }

a:hover::before {
  transform: scaleX(1);
}
</style>