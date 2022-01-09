<template>
   <div class="flex flex-col max-w-md rounded-lg bg-white bg-clip-content shadow-xl mx-6">
      <img src="../assets/illustration-hero.svg" alt="music" class="mb-5 rounded-t-lg" />
      <div class="p-5 px-12">
         <div class="mb-5">
            <h1 class="font-bold mb-2 text-dark-blue">Order Summary</h1>
            <p class="text-gray-400">
               You can now listen to millions of songs, audiobooks, and podcasts on
               any device anywhere you like!
            </p>
         </div>
         <div class="flex mb-5 justify-between align-middle bg-very-plae-blue p-4 rounded-md">
            <div class="flex">
               <img class="mr-3" src="../assets/icon-music.svg" />
               <div>
                  <h4 class="font-semibold text-dark-blue">Annual Plan</h4>
                  <p>$59.99/year</p>
               </div>
            </div>
            <span class="self-center text-sm text-bright-blue underline font-semibold cursor-pointer hover:text-btn-hover">Change</span>
         </div>
         <button class="bg-bright-blue w-full text-white font-semibold p-2 shadow-md hover:bg-btn-hover">Proceed to Payment</button>
         <br />
         <button class="text-desaturated-blue hover:text-dark-blue">Cancel Order</button>
      </div>
   </div>
</template>

<style scoped>
button {
   @apply w-full font-semibold p-3 rounded-lg text-base;
}
p{
   @apply text-desaturated-blue;
}
</style>

