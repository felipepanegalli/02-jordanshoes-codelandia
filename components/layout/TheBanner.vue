<template>
  <div id="banner">
    <p>Ganhe R$ 10,00 de desconto no frete</p>
  </div>
</template>

<script>
export default {
  name: "TheBanner"
}
</script>

<style lang="scss" scoped>
#banner {
  height: 60px;
  background: var(--black-light);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: var(--font-montserrat);
  font-weight: 500;
  font-size: 16px;
  color: var(--white);
}
</style>