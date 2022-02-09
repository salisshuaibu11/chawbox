<nav class="flex justify-between items-center">
    <ul class="hidden md:flex space-x-5">
        <li>
            <a href="/settings/about" class="text-white font-bold text-lg">About Us</a>
        </li>
        <li>
            <a href="/account/services" class="text-white font-bold text-lg">Our Services</a>
        </li>
        <li>
            <a href="/blog" class="text-white font-bold text-lg">Blog</a>
        </li>
        <li>
            <a href="/about" class="text-white font-bold text-lg">Contact</a>
        </li>
    </ul>
    <div class="flex items-center space-x-10 text-white font-bold text-lg">
        <button>
            <a href="/auth/login">Login</a>
        </button>
        <button class="border border-white hover:bg-white hover:text-black py-2 px-8">
            <a href="/auth/signup">Register</a></button>
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