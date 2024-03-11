<template>
  <div class="development__container">
    <img src="/img/development_img.png" />
    <div class="development__info">
      <h2>визуализация комплексной застройки</h2>
      <div class="development__item"><p>Визуализация жилых комплексов</p></div>
      <hr class="hr" />
      <div class="development__item">
        <p>Визуализация благоустройства территории</p>
      </div>
      <hr class="hr" />
      <MyButton class="transparent">Оставить заявку</MyButton>
    </div>
  </div>
</template>
<script>
import MyButton from './MyButton.vue';
export default {
  components: {
    MyButton,
  },
};
</script>
<style scoped>
.development__container {
  background-color: #222224;
  color: white;
  display: flex;
  flex-direction: row;
}
img {
  width: 859px;
  height: auto;
}
.development__info {
  display: flex;
  flex-direction: column;
  padding: 82px 277px 0 80px;
  gap: 40px;
}
h2 {
  font-size: 50px;
  color: #efefef;
}
.hr {
  border: 1px solid #9da0a3;
  width: 690px;
  height: 0px;
  opacity: 0.3;
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
</style>
