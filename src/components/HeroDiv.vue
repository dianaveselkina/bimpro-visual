<template>
  <div class="hero__container">
    <div class="hero__description">
      <h1 class="hero__title">Визуализация любой сложности</h1>
      <p>
        Создадим 3D Визуализации, презентационные интерактивные и VR-материалы,
        анимации, жилой и коммерческой недвижимости
      </p>
      <MyButton class="hero__btn">Рассчитать стоимость проекта</MyButton>
    </div>
    <div class="hero__slider">
      <img class="hero__img" src="/img/hero_img_1.png" alt="building" />
    </div>
  </div>
</template>
<script>
import MyButton from './MyButton.vue';

export default {
  components: {
    MyButton,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.hero__container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-end;
  gap: 200px;
  padding: 100px 277px;
  background-color: #222224;
  color: white;
}
.hero__description {
  max-width: 444px;
  display: flex;
  flex-direction: column;
}
.hero__title {
  font-size: 70px;
  text-transform: uppercase;
}
.hero__btn {
  width: 340px;
  height: 31px;
}
p {
  padding: 25px 0 50px;
}
@media (width < 480px) {
  .hero__container {
    display: flex;
    flex-direction: column;
    padding: 15px 20px;
    gap: 10px;
  }
  .hero__description {
    padding: 80px 60px;
  }
  .hero__title {
    font-size: 38px;
    text-align: center;
  }
  p {
    text-align: center;
    font-size: 13px;
  }
}
</style>
