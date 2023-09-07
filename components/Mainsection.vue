<template>
      <div class="grid grid-cols-12 items-center">
    <div class="col-span-12 md:col-span-6 bg-[#F8F8FF] h-full flex">
      <div class="w-10/12 mx-auto my-auto">
        <h2 class="text-3xl md:text-6xl font-semibold md:w-8/12">
          Contracts Made Digital
        </h2>
        <p class="text-xl text-gray-600 md:w-7/12 my-5">
          Create, sign and store all your contracts in one, safe place.
        </p>
        <form class="my-5">
          <div class="flex">
            <div class="relative w-full md:w-10/12">
              <input type="search" class="lock px-2.5 py-5 w-full z-20 text-sm text-gray-900 bg-white border-l-2 border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-l-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:border-blue-500" placeholder="Your Email Address">
              <button type="submit" class="absolute top-0 right-0 py-2.5 px-5 text-sm font-medium h-full text-white bg-blue-700 border border-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                <span class="flex items-center">
                  <svg class="w-6 h-6 text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 20">
      <path d="M14.066 0H7v5a2 2 0 0 1-2 2H0v11a1.97 1.97 0 0 0 1.934 2h12.132A1.97 1.97 0 0 0 16 18V2a1.97 1.97 0 0 0-1.934-2Zm-3 15H4.828a1 1 0 0 1 0-2h6.238a1 1 0 0 1 0 2Zm0-4H4.828a1 1 0 0 1 0-2h6.238a1 1 0 1 1 0 2Z"/>
      <path d="M5 5V.13a2.96 2.96 0 0 0-1.293.749L.879 3.707A2.98 2.98 0 0 0 .13 5H5Z"/>
    </svg>
    Get Started
                </span>
              </button>
            </div>
          </div>
        </form>
        <p>
          Or 
          <span class="text-blue-600 ml-1 hover:border-b cursor-pointer hover:border-blue-600">
            Book a Demo
          </span>
        </p>
      </div>
    </div>
    <div class="col-span-12 md:col-span-6 w-11/12 mx-auto hidden md:flex">
      <img src="https://contractbook-home-amt.netlify.app/_nuxt/hero1.d5fab3ed.jpg" class="max-w-full" alt="contract">
    </div>
  </div>
  <div class="mt-10 md:mt-2">
    <div class="flex justify-center mb-3">
      <img class="w-16" src="data:image/png;base64,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" alt="document">
    </div>
    <h4 class="text-center text-3xl md:text-4xl font-semibold">From creation</h4>
    <h4 class="text-center text-3xl md:text-4xl font-semibold mb-3">to management</h4>
    <p class="text-center text-lg text-gray-600 md:w-5/12 mx-auto md:px-7">
      Say goodbye to printers, paper and time wasted on creating, signing and storing your contacts. No more printer frustations. Contractbook makes it all digital and hassle-free.
    </p>
    <div class="my-5 md:my-10">
      <img src="https://contractbook-home-amt.netlify.app/_nuxt/fullimg.6a2e8d65.png" class="w-full" alt="contract">
    </div>
    <div class="flex justify-center">
      <button class="py-2.5 px-5 text-violet-600 hover:text-violet-700 font-semibold border border-violet-500 hover:border-violet-600">
        Watch the Video
      </button>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>