<script>
import Footer from "../components/Footer.svelte";
import Header from "../components/Header.svelte";

</script>

<Header />
<main>
    <section>
        <div class="container">
            <h1 class="pt-24 font-blak text-5xl max-w-2xl text-center mx-auto leading-snug lg:text-4xl lg:pt-16 md:text-3xl md:pt-12 md:w-full sm:pt-10 ms:text-2xl">Grow your business online.
                Get. More. Leads.</h1>
            <p class=" text-xl tracking-tight text-center max-w-xl mx-auto mt[18px] md:text-lg md:mt-4 sm:mt-2 sm:text-base">Wanna get serious into digital marketing? Then you need leads and this is where we can help you.</p>
            <div class="flex justify-center gap-7 sm:flex-col sm:gap-0 sm:mt-4">
                <a href="#" class="btn sm:text-center sm:mt-4 sm:text-base sm:max-w-full sm:text-center">Start here.</a>
                <a href="#" class="inline-block mt-6 py-[10px] px-8 rounded-2xl text-lightred text-xl tracking-tight border-2 border-lightred sm:text-center sm:mt-4 sm:text-base">Learn More</a>
            </div>
        </div>
    </section>
    <section class=" mb-16">
        <div class="container ">
            <div class=" flex justify-between mt-40 pb-33 lg:flex-col lg:mt-32 lg:pb-24">
                <div class="flex flex-col w-1/2 lg:w-full">
                    <div class="text-darkred font-bold text-xl tracking-tight  ">about us</div>
                    <h2 class=" mt-[2px] text-4xl font-black lg:text-3xl sm:text-2xl">The team behind the brand.</h2>
                    <p class="mt-[10px] max-w-sm text-lg lg:max-w-full sm:text-base ">Proin elementum fermentum auctor. Nulla semper, est eget congue pellentesque, erat nulla molestie mi, in finibus leo nisl ac lectus. Praesent non urna. Nulla congue porta lectus in laoreet. Aenean pellentesque vitae metus id porttitor.t</p>
                    <a href="#" class="btn sm:max-w-full sm:text-center">Learn more</a>
                </div>
                <div class="flex flex-col w-[450px] lg:w-full lg:mt-6  "><img src="./main.jpg" alt="main" class=""></div>
            </div>
        </div>
    </section>
</main>

<Footer />