<script>
    import {openModel} from '../store'
</script>

<header class="flex flex-col relative z-20">
    <div class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6">
        <a href="/">
            <h1 class="font-semibold">Swoley 
                <span class="text-indigo-400">Moley</span>
            </h1>
        </a>
        <button on:click={() => $openModel =true} class="md:hidden grid place-items-center">
            <i class="fa-solid fa-bars"></i>
        </button>
        <nav class="hidden md:flex items-center gap-4 lg:gap-6">
            <a href="#Product" class="duration-200 hover:text-indigo-400 cursor-pointer">Product</a>
            <a href="#Reviews" class="duration-200 hover:text-indigo-400 cursor-pointer">Reviews</a>
            <a href="#Faqs" class="duration-200 hover:text-indigo-400 cursor-pointer">Faqs</a>
            <button class="specialBtn">
                <p>Start Free Today</p>
            </button>
        </nav>
    </div>
</header>

