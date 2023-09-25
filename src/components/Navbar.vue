<template>
<nav class="flex justify-between items-center">
    <h1 class="lg:text-3xl text-xl font-extrabold text-white">Suzzy's Kitchen</h1>

    <div class="hidden lg:flex gap-5 text-stone-400">
        <a href="" class="hover:text-white transition-all duration-300">Menu</a>
        <a href="" class="hover:text-white transition-all duration-300">Services</a>
        <a href="" class="hover:text-white transition-all duration-300">Reservation</a>
        <a href="" class="hover:text-white transition-all duration-300">Blog</a>
        <a href="" class="hover:text-white transition-all duration-300">Contact</a>
    </div>

    <div class="hidden lg:flex gap-5 items-center">
        <div class="relative">
            <svg xmlns="http://www.w3.org/2000/svg" class="hover:text-white transition-all duration-300 text-stone-400 cursor-pointer" width="36" height="36" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                <path d="M6.331 8h11.339a2 2 0 0 1 1.977 2.304l-1.255 8.152a3 3 0 0 1 -2.966 2.544h-6.852a3 3 0 0 1 -2.965 -2.544l-1.255 -8.152a2 2 0 0 1 1.977 -2.304z"></path>
                <path d="M9 11v-5a3 3 0 0 1 6 0v5"></path>
            </svg>
            <span class="bg-red-600 text-white h-5 flex items-center justify-center w-5 text-xs absolute -top-2 left-5 rounded-full">
                0
            </span>
        </div>
        <button class="bg-[#FFCC00] py-1.5 px-6 text-gray-900 rounded-full">Reservation</button>
    </div>
    <Mobile />
</nav>
</template>

<script>
import Mobile from './Mobile.vue';
export default {
    components: {
        Mobile
    }
}
</script>
