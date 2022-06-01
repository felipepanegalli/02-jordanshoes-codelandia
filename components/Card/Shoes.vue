<template>
  <div>
    <img :src="imagesrc" :alt="alt">
  </div>
</template>

<script>
export default {
  name: "Shoes",
  props: {
    imagesrc: {
      type: String,
      required: true
    },
    alt: {
      type: String,
      default: ''
    },
  }
}
</script>

<style lang="scss" scoped>
div {
  height: 300px;
  background: var(--gray-light);
}
</style>