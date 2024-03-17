<template>
  <div class="media__container">
    <h2 class="services__title">СМИ о нас</h2>
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
.services__title {
  text-transform: uppercase;
  font-size: 50px;
  padding: 27px 0 80px;
}
.medias__cards {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
</style>
