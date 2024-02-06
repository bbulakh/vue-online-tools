<script>

export default {
  props: {
    btnText: String,
    bgColor: String,
    textColor: String,
    url: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <a :href="url" :class="['w-full', 'py-3', 'text-center', 'rounded-md', bgColor, textColor]">
    {{ btnText }}
  </a>
</template>

<style scoped>
button,
a {
  font-family: 'Koulen';
}
</style>
