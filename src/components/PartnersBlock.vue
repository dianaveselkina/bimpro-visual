<template>
  <div class="partners__container">
    <h2 class="services__title">наши партнеры</h2>
    <div class="services__cards">
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img1.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img2.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img3.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img4.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img5.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img6.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img7.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img8.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img9.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img10.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img11.png" alt="logo" />
      </div>
      <div class="services__card">
        <img class="logo__img" src="/img/partners_img12.png" alt="logo" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.partners__container {
  padding: 100px 277px;
  background-color: #2e2e31;
  color: white;
}
.services__title {
  text-transform: uppercase;
  font-size: 50px;
  padding: 27px 0 80px;
}
.services__card {
  display: flex;
  align-items: center;
  width: 228px;
  height: 200px;
  border: 1px solid #9da0a3;
}
.services__cards {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
}
</style>
