<script>

export default {
  props: {
    btnText: String,
    bgColor: String,
    textColor: String,
  }
}
</script>

<template>
  <button :class="['w-full', 'py-3', 'rounded-md', bgColor, textColor]">
    {{ btnText }}
  </button>
</template>

<style scoped>
button,
a {
  font-family: 'Koulen';
}
</style>
