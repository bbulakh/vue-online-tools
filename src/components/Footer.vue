<template>
  <footer class="bg-[#242424] text-white">
    <div class="p-[2rem]">
        <img class="w-1/2" src="/public/images/logo-inverted.svg" alt="Cools inverted logo">
        <p class="text-white w-1/2">Cools is a bunch of useful and fun tools that you can use for your purposes</p>
        
        <div class="flex flex-col">
            <h2>Feel free to send me a feedback</h2>
            <textarea class="text-black p-2" name="" id="" cols="30" rows="5"></textarea>
            <button>SEND MESSAGE</button>
        </div>
    </div>


    <div class="flex justify-center items-center text-black bg-[#A8EB53]">
      <h2>{{ new Date().getFullYear() }}, Bogdan Bulakh</h2>
    </div>
  </footer>
</template>
