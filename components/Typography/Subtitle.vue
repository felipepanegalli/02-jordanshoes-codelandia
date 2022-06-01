<template>
<p>
  <slot></slot>
</p>
</template>

<script>
export default {
  name: "Subtitle"
}
</script>

<style lang="scss" scoped>
p {
  font-weight: 500;
  font-size: 16px;
  font-family: var(--font-montserrat);
  line-height: 30px;
}
</style>