<template>
  <div id="titleContainer">
    <p>JordanShoes</p>
  </div>
</template>

<script>
export default {
  name: "TheTitle"
}
</script>

<style lang="scss" scoped>
#titleContainer {
  height: 60px;
  background: var(--white-200);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: var(--font-montserrat);
  font-weight: 600;
  font-size: 24px;
  color: var(--black-light);
}
</style>