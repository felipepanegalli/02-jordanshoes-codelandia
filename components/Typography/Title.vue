<template>
  <h1>
    <slot></slot>
  </h1>
</template>

<script>
export default {
  name: "Title"
}
</script>

<style lang="scss" scoped>
h1 {
  font-weight: 600;
  font-size: 28px;
  font-family: var(--font-montserrat);
}
</style>