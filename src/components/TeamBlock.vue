<template>
  <div class="services__container">
    <h2 class="services__title">Команда BIM<span>PRO</span></h2>
    <p>
      Главные действующие лица, именно они создают визуализации и наполняют кадр
      жизнью.
    </p>
    <div class="services__cards">
      <TeamCard
        imageUrl="/img/team_img1.png"
        text="Никитин Максим"
        text1="Ведущий визуализатор"
      />
      <TeamCard
        imageUrl="/img/team_img2.png"
        text="Ратникова Екатерина"
        text1="Художник-визуализатор"
      />
      <TeamCard
        imageUrl="/img/team_img3.png"
        text="Полина Мустафина"
        text1="Художник-визуализатор"
      />
      <TeamCard
        imageUrl="/img/team_img4.png"
        text="Егоров Александр"
        text1="Архитектор"
      />
      <TeamCard
        imageUrl="/img/team_img5.png"
        text="Анна Бендер"
        text1="Визуализатор-моделлер"
      />
      <TeamCard
        imageUrl="/img/team_img6.png"
        text="Ксения Воронцова"
        text1="Художник-визуализатор"
      />
      <TeamCard
        imageUrl="/img/team_img7.png"
        text="Светлана Михеева"
        text1="Руководитель проекта"
      />
      <TeamCard
        imageUrl="/img/team_img8.png"
        text="Андрей Кудрин"
        text1="Bim-менержер"
      />
    </div>
  </div>
</template>
<script>
import TeamCard from './TeamCard.vue';

export default {
  components: {
    TeamCard,
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
</style>
