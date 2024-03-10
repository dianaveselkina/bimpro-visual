<template>
  <div class="hero__container">
    <div class="hero__description">
      <h1 class="hero__title">Визуализация любой сложности</h1>
      <p>
        Создадим 3D Визуализации, презентационные интерактивные и VR-материалы,
        анимации, жилой и коммерческой недвижимости
      </p>
      <MyButton>Рассчитать стоимость проекта</MyButton>
    </div>
    <div class="hero__slider">
      <img class="hero__img" src="../img/hero_img_1.png" alt="building" />
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
  max-width: 400px;
  display: flex;
  flex-direction: column;
}
.hero__title {
  font-size: 70px;
}
p {
  padding: 25px 0 50px;
}
</style>
