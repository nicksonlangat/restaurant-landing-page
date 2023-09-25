<template>
  <div class="mx-auto container font-base text-white pb-10">
      <Navbar />
      <div class="lg:mt-20 mt-10">
          <div class="flex flex-col items-center justify-center lg:text-8xl text-4xl">
              <h1>Fresh and Healthy</h1>
              <h1>Food Specialties</h1>
              <p class="text-stone-400 mt-5 lg:text-lg text-sm text-center">We offer a wide variety of healthy and tasty meals <br> served just for you. We also deliver to your doorstep.</p>
              <img class="mt-20" src="../assets/2.png" alt="">
          </div>
          <div class="flex mt-20 flex-col items-center justify-center">
            <h3 class="lg:text-5xl text-4xl text-center">Try our new food menu</h3>
            <p class="text-stone-400 mt-5">Professionaly made with love</p>
            <div class="flex flex-col lg:flex-row gap-5">
              <img src="../assets/3.png" alt="">
              <div class="mt-20 flex flex-col gap-5">
                <h3 class="text-5xl text-center">Fried Rice With Meat <br class="hidden lg:block"> and Vegetables</h3>
                <p class="text-center text-stone-400">This combination is tasty, full of nutrients and pocket friendly.</p>
                <h3 class="text-[#FFCC00] text-center text-5xl mt-10">KSH 500</h3>
              </div>
            </div>
          </div>
          <h3 class="text-center text-5xl font-extrabold mt-20">Today's menu</h3>
          <div class="grid mt-32 lg:grid-cols-4 gap-16 gap-y-20 mx-10 lg:mx-0">
              <div class="bg-[#595959]/10 relative h-96 rounded-xl">
                  <img src="../assets/3.png" class="absolute -top-20 -left-16" alt="">
                  <div class="absolute bottom-5 mx-5">
                      <h3 class="lg:text-2xl">Butter bread mixed with vegetables</h3>
                      <div class="flex mt-10 justify-between items-center">
                          <p class="text-[#FFCC00] text-2xl font-extrabold">KSH 300</p>
                          <svg xmlns="http://www.w3.org/2000/svg" width="36" class="cursor-pointer" height="36" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                              <path d="M12 2l.324 .001l.318 .004l.616 .017l.299 .013l.579 .034l.553 .046c4.785 .464 6.732 2.411 7.196 7.196l.046 .553l.034 .579c.005 .098 .01 .198 .013 .299l.017 .616l.005 .642l-.005 .642l-.017 .616l-.013 .299l-.034 .579l-.046 .553c-.464 4.785 -2.411 6.732 -7.196 7.196l-.553 .046l-.579 .034c-.098 .005 -.198 .01 -.299 .013l-.616 .017l-.642 .005l-.642 -.005l-.616 -.017l-.299 -.013l-.579 -.034l-.553 -.046c-4.785 -.464 -6.732 -2.411 -7.196 -7.196l-.046 -.553l-.034 -.579a28.058 28.058 0 0 1 -.013 -.299l-.017 -.616c-.003 -.21 -.005 -.424 -.005 -.642l.001 -.324l.004 -.318l.017 -.616l.013 -.299l.034 -.579l.046 -.553c.464 -4.785 2.411 -6.732 7.196 -7.196l.553 -.046l.579 -.034c.098 -.005 .198 -.01 .299 -.013l.616 -.017c.21 -.003 .424 -.005 .642 -.005zm0 6a1 1 0 0 0 -1 1v2h-2l-.117 .007a1 1 0 0 0 .117 1.993h2v2l.007 .117a1 1 0 0 0 1.993 -.117v-2h2l.117 -.007a1 1 0 0 0 -.117 -1.993h-2v-2l-.007 -.117a1 1 0 0 0 -.993 -.883z" fill="currentColor" stroke-width="0"></path>
                          </svg>
                      </div>
                  </div>
              </div>
              <div class="bg-[#595959]/10 relative h-96 rounded-xl">
                  <img src="../assets/3.png" class="absolute -top-20 -left-16" alt="">
                  <div class="absolute bottom-5 mx-5">
                      <h3 class="text-2xl">Butter bread mixed with vegetables</h3>
                      <div class="flex mt-10 justify-between items-center">
                          <p class="text-[#FFCC00] text-2xl font-extrabold">KSH 300</p>
                          <svg xmlns="http://www.w3.org/2000/svg" width="36" class="cursor-pointer" height="36" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                              <path d="M12 2l.324 .001l.318 .004l.616 .017l.299 .013l.579 .034l.553 .046c4.785 .464 6.732 2.411 7.196 7.196l.046 .553l.034 .579c.005 .098 .01 .198 .013 .299l.017 .616l.005 .642l-.005 .642l-.017 .616l-.013 .299l-.034 .579l-.046 .553c-.464 4.785 -2.411 6.732 -7.196 7.196l-.553 .046l-.579 .034c-.098 .005 -.198 .01 -.299 .013l-.616 .017l-.642 .005l-.642 -.005l-.616 -.017l-.299 -.013l-.579 -.034l-.553 -.046c-4.785 -.464 -6.732 -2.411 -7.196 -7.196l-.046 -.553l-.034 -.579a28.058 28.058 0 0 1 -.013 -.299l-.017 -.616c-.003 -.21 -.005 -.424 -.005 -.642l.001 -.324l.004 -.318l.017 -.616l.013 -.299l.034 -.579l.046 -.553c.464 -4.785 2.411 -6.732 7.196 -7.196l.553 -.046l.579 -.034c.098 -.005 .198 -.01 .299 -.013l.616 -.017c.21 -.003 .424 -.005 .642 -.005zm0 6a1 1 0 0 0 -1 1v2h-2l-.117 .007a1 1 0 0 0 .117 1.993h2v2l.007 .117a1 1 0 0 0 1.993 -.117v-2h2l.117 -.007a1 1 0 0 0 -.117 -1.993h-2v-2l-.007 -.117a1 1 0 0 0 -.993 -.883z" fill="currentColor" stroke-width="0"></path>
                          </svg>
                      </div>
                  </div>
              </div>
              <div class="bg-[#595959]/10 relative h-96 rounded-xl">
                  <img src="../assets/3.png" class="absolute -top-20 -left-16" alt="">
                  <div class="absolute bottom-5 mx-5">
                      <h3 class="text-2xl">Butter bread mixed with vegetables</h3>
                      <div class="flex mt-10 justify-between items-center">
                          <p class="text-[#FFCC00] text-2xl font-extrabold">KSH 300</p>
                          <svg xmlns="http://www.w3.org/2000/svg" width="36" class="cursor-pointer" height="36" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                              <path d="M12 2l.324 .001l.318 .004l.616 .017l.299 .013l.579 .034l.553 .046c4.785 .464 6.732 2.411 7.196 7.196l.046 .553l.034 .579c.005 .098 .01 .198 .013 .299l.017 .616l.005 .642l-.005 .642l-.017 .616l-.013 .299l-.034 .579l-.046 .553c-.464 4.785 -2.411 6.732 -7.196 7.196l-.553 .046l-.579 .034c-.098 .005 -.198 .01 -.299 .013l-.616 .017l-.642 .005l-.642 -.005l-.616 -.017l-.299 -.013l-.579 -.034l-.553 -.046c-4.785 -.464 -6.732 -2.411 -7.196 -7.196l-.046 -.553l-.034 -.579a28.058 28.058 0 0 1 -.013 -.299l-.017 -.616c-.003 -.21 -.005 -.424 -.005 -.642l.001 -.324l.004 -.318l.017 -.616l.013 -.299l.034 -.579l.046 -.553c.464 -4.785 2.411 -6.732 7.196 -7.196l.553 -.046l.579 -.034c.098 -.005 .198 -.01 .299 -.013l.616 -.017c.21 -.003 .424 -.005 .642 -.005zm0 6a1 1 0 0 0 -1 1v2h-2l-.117 .007a1 1 0 0 0 .117 1.993h2v2l.007 .117a1 1 0 0 0 1.993 -.117v-2h2l.117 -.007a1 1 0 0 0 -.117 -1.993h-2v-2l-.007 -.117a1 1 0 0 0 -.993 -.883z" fill="currentColor" stroke-width="0"></path>
                          </svg>
                      </div>
                  </div>
              </div>
              <div class="bg-[#595959]/10 relative h-96 rounded-xl">
                  <img src="../assets/3.png" class="absolute -top-20 -left-16" alt="">
                  <div class="absolute bottom-5 mx-5">
                      <h3 class="text-2xl">Butter bread mixed with vegetables</h3>
                      <div class="flex mt-10 justify-between items-center">
                          <p class="text-[#FFCC00] text-2xl font-extrabold">KSH 300</p>
                          <svg xmlns="http://www.w3.org/2000/svg" width="36" class="cursor-pointer" height="36" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                              <path d="M12 2l.324 .001l.318 .004l.616 .017l.299 .013l.579 .034l.553 .046c4.785 .464 6.732 2.411 7.196 7.196l.046 .553l.034 .579c.005 .098 .01 .198 .013 .299l.017 .616l.005 .642l-.005 .642l-.017 .616l-.013 .299l-.034 .579l-.046 .553c-.464 4.785 -2.411 6.732 -7.196 7.196l-.553 .046l-.579 .034c-.098 .005 -.198 .01 -.299 .013l-.616 .017l-.642 .005l-.642 -.005l-.616 -.017l-.299 -.013l-.579 -.034l-.553 -.046c-4.785 -.464 -6.732 -2.411 -7.196 -7.196l-.046 -.553l-.034 -.579a28.058 28.058 0 0 1 -.013 -.299l-.017 -.616c-.003 -.21 -.005 -.424 -.005 -.642l.001 -.324l.004 -.318l.017 -.616l.013 -.299l.034 -.579l.046 -.553c.464 -4.785 2.411 -6.732 7.196 -7.196l.553 -.046l.579 -.034c.098 -.005 .198 -.01 .299 -.013l.616 -.017c.21 -.003 .424 -.005 .642 -.005zm0 6a1 1 0 0 0 -1 1v2h-2l-.117 .007a1 1 0 0 0 .117 1.993h2v2l.007 .117a1 1 0 0 0 1.993 -.117v-2h2l.117 -.007a1 1 0 0 0 -.117 -1.993h-2v-2l-.007 -.117a1 1 0 0 0 -.993 -.883z" fill="currentColor" stroke-width="0"></path>
                          </svg>
                      </div>
                  </div>
              </div>
          </div>
          <div class="flex items-center justify-center mt-5">
            <button class="bg-[#FFCC00] text-stone-900 uppercase py-2 px-6 rounded-md">see all</button>
          </div>
          <div class="grid lg:grid-cols-2 gap-5 mx-5 lg:mx-0 mt-20">
            <div>
              <img src="../assets/3.png" alt="">
            </div>
            <div>
              <h3 class="lg:text-7xl text-4xl text-center lg:text-start">Whole wheat bread with avocado sauce</h3>
              <ul class="flex flex-col gap-4 mt-5 list-disc ml-5 text-stone-400">
                <li>2 slices of whole wheat bread</li>
                <li>2 eggs (can be domestic or native chicken)</li>
                <li>1 avocado</li>
                <li>Enough black pepper</li>
                <li>Enough chili powder</li>
                <li>Enough salt</li>
                <li>As needed parsley dry powder</li>
                <li>Enough cooking oil</li>
              </ul>
            </div>
          </div>
      </div>
  </div>
  </template>
  
  <script>
  import Navbar from '@/components/Navbar.vue'
  export default {
      name: 'HomeView',
      components: {
          Navbar
      }
  }
  </script>
  
  <style>
  body,
  html {
      background-color: #101015;
  }
  </style>
  