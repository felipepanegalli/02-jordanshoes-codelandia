<template>
  <LayoutTheBanner>
    <p>Ganhe R$ 10,00 de desconto no frete</p>
  </LayoutTheBanner>
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

    <div class="shoes-container">
      <CardShoes imagesrc="/assets/images/1.png" alt="Jordan 1" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/2.png" alt="Jordan 2" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/3.png" alt="Jordan 3" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/4.png" alt="Jordan 4" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/5.png" alt="Jordan 5" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/6.png" alt="Jordan 6" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/7.png" alt="Jordan 7" data-aos="zoom-in" data-aos-duration="1000" />
      <CardShoes imagesrc="/assets/images/8.png" alt="Jordan 8" data-aos="zoom-in" data-aos-duration="1000" />
    </div>

  </UtilsContainer>
  <LayoutTheBanner>
    <p>Todos os direitos reservados.</p>
  </LayoutTheBanner>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';

export default {
  mounted() {
    AOS.init();
  }
}
</script>

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

.shoes-container {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
  justify-content: center;
  margin-bottom: 100px;
}
</style>