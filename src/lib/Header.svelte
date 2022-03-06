<script>
    import Navbar from "$lib/Navbar.svelte";
    import HeroSection from "$lib/HeroSection.svelte";
    import { onMount } from "svelte";
    
    const images = ['/images/heroImage.png', '/images/heroImage1.png', '/images/heroImage2.png'];
    let background = 'heroImage';

    onMount(() => {
        const hero = document.getElementById("hero");
        let interval = 0;

        setInterval(() => {
            if (interval <= images.length - 2) {
                interval++
            } else {
                interval = 0;
            }
            hero.style.backgroundImage = `url(${images[interval]})`;
        }, 5000);
    })
</script>
<section id="hero" class={`mb-0 h-fit overflow-hidden transition-all delay-150 bg-no-repeat bg-cover bg-center py-12 lg:px-40 px-10 md:px-10  bg-blend-multiply w-screen`}>
    <Navbar />
    <HeroSection />
</section>