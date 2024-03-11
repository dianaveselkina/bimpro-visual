<template>
  <div class="development__container">
    <img src="/img/development_img.png" />
    <div class="development__info">
      <h2>визуализация комплексной застройки</h2>
      <div class="development__item"><p>Визуализация жилых комплексов</p></div>
      <div class="development__item">
        <p>Визуализация благоустройства территории</p>
      </div>
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
<style scoped></style>
