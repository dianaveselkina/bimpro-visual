<template>
  <div class="card">
    <img :src="imageUrl" alt="icons" />
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
  padding: 44px 50px 34px;
  width: 321px;
  height: 295px;
  border: solid 1px #464646;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 22px;
  font-size: 22px;
}
.card:hover {
  cursor: pointer;
  background-color: #ea4c14;
}
img {
  max-width: 100%;
  width: auto;
  height: 70px;
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
.card__text {
  text-align: center;
}
</style>
