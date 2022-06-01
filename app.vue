<template>
  <LayoutTheBanner/>
  <LayoutTheTitle/>
  <CardBanner/>
  <UtilsContainer>
    <div class="container">
      <TypographyTitle>
        Destaques
      </TypographyTitle>
      <TypographySubtitle style="color: var(--gray)">
        Frete grátis e chinelo de brinde é aqui, aproveite por tempo limitado.
      </TypographySubtitle>
    </div>

    <CardShoes imagesrc="/assets/images/1.png" alt="abc"/>

  </UtilsContainer>
</template>

<style lang="scss" scoped>
.container {
  text-align: center;
  height: 220px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 1rem;
}
</style>