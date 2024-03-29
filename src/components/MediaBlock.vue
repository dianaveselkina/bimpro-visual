<template>
  <div class="media__container">
    <div class="title">
      <h2 class="services__title">СМИ о нас</h2>
      <div class="switch">
        <div class="switch__block">
          <img class="arrow__img" src="/img/arrow_icon1.png" alt="arrow" />
        </div>
        <div class="switch__block">
          <img class="arrow__img" src="/img/arrow_icon2.png" alt="arrow" />
        </div>
      </div>
    </div>
    <div class="medias__cards">
      <MediaCard
        imageUrl="/img/media_img1.png"
        text="Бюджет придаст импульс BIM"
      />
      <MediaCard
        imageUrl="/img/media_img2.png"
        text="Социалка не успевает
за технологиями"
      />
      <MediaCard imageUrl="/img/media_img1.png" text="BIM как религия" />
      <MediaCard
        imageUrl="/img/media_img2.png"
        text="Благоустройство на самый взыскательный вкус"
      />
    </div>
  </div>
</template>
<script>
import MediaCard from './MediaCard.vue';
export default {
  components: {
    MediaCard,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.media__container {
  padding: 100px 277px;
  background-color: #2e2e31;
  color: white;
}
.title {
  padding: 27px 0 80px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.switch {
  display: flex;
  flex-direction: row;
}
.switch__block {
  cursor: pointer;
  width: 50px;
  height: 50px;
  border: 1px solid #9da0a3;
}
.services__title {
  text-transform: uppercase;
  font-size: 50px;
}
.medias__cards {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
@media (width < 480px) {
  .media__container {
    display: none;
  }
}
</style>
