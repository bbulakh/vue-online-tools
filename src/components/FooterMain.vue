<script setup>
import ButtonPrimary from './ButtonPrimary.vue'
</script>

<template>
  <footer class="bg-[#242424] text-white">
    <div class="p-[2rem] flex flex-col gap-4">
      <div>
        <img
          class="w-1/2 mb-2"
          src="/src/assets/images/logo-inverted.svg"
          alt="Cools inverted logo"
        />
        <p class="text-white w-5/6">
          Cools is a bunch of useful and fun tools that you can use for your purposes
        </p>
      </div>

      <div class="flex flex-col">
        <h2 class="text-3xl text-left mb-3">FEEL FREE to share your feedback</h2>

        <form class="flex flex-col gap-3">
          <input class="p-2" type="text" placeholder="Enter Your Name" />
          <input class="p-2" type="text" placeholder="E-mail" />
          <textarea
            class="text-black p-2"
            placeholder="Write your ideas here..."
            name=""
            id=""
            cols="30"
            rows="5"
          ></textarea>
          <ButtonPrimary bgColor="bg-[#EA985D]" btnText="SEND FEEDBACK" textColor="text-white" />
        </form>
      </div>
    </div>

    <div class="flex justify-center items-center text-[#242424] bg-[#A8EB53]">
      <h2 class="py-2">{{ new Date().getFullYear() }}, Bogdan Bulakh</h2>
    </div>
  </footer>
</template>
