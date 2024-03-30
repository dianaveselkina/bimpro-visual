<template>
  <div class="visual__container">
    <img :src="imageUrl" alt="building" />
    <div class="visual__info">
      <h2>{{ title }}</h2>
      <div class="visual__item">
        <p>{{ text1 }}</p>
      </div>
      <div class="visual__item">
        <p>{{ text2 }}</p>
      </div>
      <MyButton class="transparent">Оставить заявку</MyButton>
    </div>
  </div>
</template>
<script>
import MyButton from './MyButton.vue';
export default {
  props: {
    title: String,
    text1: String,
    text2: String,
    imageUrl: String,
  },
  components: {
    MyButton,
  },
};
</script>
<style scoped>
.visual__container {
  background: #2e2e31;
  color: white;
  display: flex;
  flex-direction: row;
}
img {
  position: relative;
  width: 859px;
  height: auto;
}
.visual__info {
  display: flex;
  flex-direction: column;
  padding: 82px 277px 0 80px;
  gap: 40px;
}
.visual__item {
  display: flex;
  flex-direction: row;
  padding-bottom: 35px;
  border-bottom: 1px solid #9da0a3;
}
h2 {
  font-size: 50px;
  color: #efefef;
}
.transparent {
  background-color: rgba(28, 28, 28, 0);
  border: 2px solid #f5f5f5;
  border-radius: 6px;
  padding: 4px 35px 0px 35px;
  width: 320px;
  height: 70px;
}
.transparent:hover {
  background-color: #ea4c14;
  border: 2px solid #ea4c14;
}
@media (width < 480px) {
  .visual__container {
    background: #2e2e31;
    padding: 0 20px 37px;
    display: flex;
    flex-direction: column;
  }
  h2 {
    font-size: 40px;
    text-align: center;
    padding: 0px 24px;
  }
  .visual__info {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 40px;
    padding: 0;
  }
}
</style>
