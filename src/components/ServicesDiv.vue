<template>
  <div class="services__container">
    <h2 class="services__title">наши услуги</h2>
    <div class="services__cards">
      <CardServices
        imageUrl="/img/services_img_1.png"
        text="Визуализация
комплексной застройки"
      />
      <CardServices
        imageUrl="/img/services_img_2.png"
        text="Архитектурная
визуализация"
      />
      <CardServices
        imageUrl="/img/services_img_3.png"
        text="Интерьерная
визуализация"
      />
      <CardServices
        imageUrl="/img/services_img_4.png"
        text="Предметная и рекламная
визуализация"
      />
      <CardServices
        imageUrl="/img/services_img_5.png"
        text="3D, VR и видео
материалы"
      />
      <CardServices
        imageUrl="/img/services_img_6.png"
        text="Дополнительные
материалы"
      />
    </div>
  </div>
</template>
<script>
import CardServices from './CardServices.vue';

export default {
  components: {
    CardServices,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.services__container {
  padding: 100px 277px;
  background-color: #222224;
  color: white;
}
.services__title {
  text-transform: uppercase;
  font-size: 50px;
  padding: 27px 0 80px;
}
.services__cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 29px 26px;
}
@media (width < 480px) {
  .services__container {
    padding: 75px 20px 43px;
    background: #2e2e31;
  }
  .services__title {
    display: none;
  }
  .services__cards {
    display: flex;
    flex-direction: column;
  }
}
</style>
