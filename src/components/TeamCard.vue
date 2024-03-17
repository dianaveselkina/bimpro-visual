<template>
  <div class="card">
    <img :src="imageUrl" alt="foto" />
    <div class="card__text">
      <p class="card__text1">{{ text }}</p>
      <p class="card__text2">{{ text1 }}</p>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    text: String,
    text1: String,
    imageUrl: String,
  },
};
</script>
<style scoped>
.card {
  width: 319px;
  height: 501px;
  border-radius: 5px;
  border: solid 3px #464646;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.card__text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  width: 319px;
  height: 94px;
  background-color: #2e2e31;
  border-top: 1px solid #ea4c14;
}
.card__text1 {
  font-size: 22px;
  color: #ea4c14;
}
.card__text2 {
  font-size: 18px;
  color: #fff;
}
img {
  max-width: 100%;
  width: auto;
  height: 404px;
}
</style>
