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
  height: 302px;
  background: var(--gray-light);
  width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  transition: transform .5s !important;
  border-radius: 5px;

  &:hover{
    transform: scale(1.1) !important;
    box-shadow: 0 0 5px rgba(71, 71, 71, 0.5);
  }
}

img {
  max-height: 50%;
}
</style>