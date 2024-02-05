<script>
export default {
  props: {
    bgColor: String,
    textColor: String
  }
}
</script>

<template>
  <button
    :class="[
      'w-full',
      'flex',
      'justify-center',
      'items-center',
      'gap-2',
      'py-3',
      'rounded-md',
      bgColor,
      textColor
    ]"
  >
    <slot name="icon"></slot>
    <slot><span></span></slot>
  </button>
</template>

<style scoped>
button,
a {
  font-family: 'Koulen';
}
</style>
