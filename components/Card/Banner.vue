<template>
  <div id="banner">
    <h1>A melhor loja de Jordan</h1>
    <p>O tênis Jordan é fruto de uma velha e forte parceria entre a Nike e o jogador Michael Jordan.</p>
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style lang="scss" scoped>
#banner {
  height: 337px;
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), url("~/assets/images/wallpaper.jpeg") no-repeat;
  color: var(--white);
  font-family: var(--font-montserrat);
  padding: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  line-height: 30px;
  gap: 1rem;

  h1 {
    font-size: 28px;
    font-weight: 700;
  }

  p {
    font-size: 16px;
    font-weight: 600;
  }
}
</style>