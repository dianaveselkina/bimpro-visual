<template>
  <div class="card">
    <img :src="imageUrl" alt="foto" />
    <p>02.11.2022</p>
    <p class="card__text">{{ text }}</p>
    <div class="arrow">
      <p class="arrow__text">Читать</p>
      <img class="arrow__img" src="/img/arrow_white.png" alt="arrow" />
    </div>
  </div>
</template>
<script>
export default {
  props: {
    text: String,
    imageUrl: String,
  },
};
</script>
<style scoped>
.card {
  width: 319px;
  height: 474px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 22px;
  font-size: 22px;
}
.card:hover {
  cursor: pointer;
}
img {
  max-width: 100%;
  width: auto;
  height: 319px;
}
.arrow {
  display: flex;
  flex-direction: row;
  gap: 20px;
}
.arrow__img {
  width: 29px;
  height: auto;
}
</style>
