<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template> 
  <div class="header text-gray-100">
    <div class="relative">
      <img class="m-auto rounded-lg" src="../assets/images/6.jpg" alt="">
      <div class="absolute absolute z-40 inset-x-0 -bottom-14 flex items-center justify-center text-white text-xl font-bold">
        <h1 class="tittle-hero text-4xl text-center font-serif">
            <p>Track games you’ve watched.</p>
            <p>Save those you want to play.</p>
            <p>Tell your friends what’s good.</p>
            <div class="button-register mt-10 ">
              <button class="bg-green-400 hover:bg-green-500 rounded-md px-3 text-2xl font-sans">
                 REGISTER NOW
              </button>
            </div>
            <!-- <a class="m-auto underline font-bold" href="">user</a> -->
            <!-- <p>heres what weve been waiting for u ...</p> -->
          </h1>
      </div>
    </div>
    <section class="m-auto pt-18 w-[950px]">
      <div class="content-wrap">
        <section class="section-poster mt-20">
          <div class="sub-heading-poster flex justify-between border-b-4 border-gray-400 ">
            <h2 class="subsection-poster">
              New on Gameboxd
            </h2>
            <a href="">For you</a>
          </div>
            
          <ul class="poster-list flex justify-between my-4 ">
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/1.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/2.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/3.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/4.jpg" alt=""></a></li>
              <li class="hover:scale-125"><a href="/PROFILE"><img class="w-[150px] h-[225px] rounded-lg" src="../assets/images/5.jpg" alt=""></a></li>
          </ul>
          <div class="section-information-header pt-10">
            <h1 class="">
              Gamebox lets you...
            </h1>
          </div>
          <div class="section-information flex flex-wrap justify-around text-center ">
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">Keep track of every game youve ever play</h1></div>
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">show some love for your favorite games and reviews</h1></div>
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">Write reviews and follow friends</h1></div>
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">Rate each game on a five star scale</h1></div>
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">Keep a diary of yours games and the progress on them</h1></div>
            <div class="w-[310px] h-[102px] bg-gray-600 my-5 flex items-center rounded-md"><h1 class="px-2">Create lists and share it to everyone</h1> </div>
          </div>
        </section>
      </div>
    </section>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
