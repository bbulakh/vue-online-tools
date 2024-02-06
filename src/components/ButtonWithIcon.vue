<script>
export default {
  props: {
    bgColor: String,
    textColor: String,
    url: {
      type: String,
      required: true
    }
  },
}
</script>

<template>
  <a :href="url"
  rel="nofollow"
  target="_blank"
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
  </a>
</template>

<style scoped>
button,
a {
  font-family: 'Koulen';
}
</style>
