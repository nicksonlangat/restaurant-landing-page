<template>
<button @click="openModal" class="text-white lg:hidden">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
    </svg>
</button>
<TransitionRoot appear :show="isOpen" as="template">
    <Dialog as="div" @close="closeModal" class="relative z-10">
        <TransitionChild as="template" enter="duration-300 ease-out" enter-from="opacity-0" enter-to="opacity-100" leave="duration-200 ease-in" leave-from="opacity-100" leave-to="opacity-0">
            <div class="fixed inset-0 bg-black bg-opacity-25" />
        </TransitionChild>

        <div class="fixed inset-0 overflow-y-auto">
            <div class="flex mt-16 items-center p-4 text-center">
                <TransitionChild as="template" enter="duration-300 ease-out" enter-from="opacity-0 scale-95" enter-to="opacity-100 scale-100" leave="duration-200 ease-in" leave-from="opacity-100 scale-100" leave-to="opacity-0 scale-95">
                    <DialogPanel class="w-full font-base max-w-md transform overflow-hidden h-96 rounded-xl bg-[#101015] p-6 text-left align-middle shadow-xl transition-all">
                        <div class="flex justify-end items-end text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" @click="closeModal" class="w-8 h-8">
  <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
</svg>

                        </div>
                        <div class="flex flex-col gap-5 text-stone-400">
        <a href="" class="hover:text-white transition-all duration-300">Menu</a>
        <a href="" class="hover:text-white transition-all duration-300">Services</a>
        <a href="" class="hover:text-white transition-all duration-300">Reservation</a>
        <a href="" class="hover:text-white transition-all duration-300">Blog</a>
        <a href="" class="hover:text-white transition-all duration-300">Contact</a>
    </div>
    <div class="flex gap-10 mt-16 items-center">
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
        <button class="bg-[#FFCC00] py-1.5 px-6 rounded-full">Reservation</button>
    </div>
                    </DialogPanel>
                </TransitionChild>
            </div>
        </div>
    </Dialog>
</TransitionRoot>
</template>

<script>
import {
    TransitionRoot,
    TransitionChild,
    Dialog,
    DialogPanel,
    DialogTitle,
} from '@headlessui/vue'

export default {
    components: {
        TransitionRoot,
        TransitionChild,
        Dialog,
        DialogPanel,
        DialogTitle,
    },
    data() {
        return {
            isOpen: false
        }
    },
    methods: {
        openModal() {
            this.isOpen = true
        },
        closeModal() {
            this.isOpen = false
        }
    }
}
</script>
