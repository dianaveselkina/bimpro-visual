<template>
  <div class="project__container">
    <h2>Какие проекты мы уже реализовали?</h2>
    <div class="tags__block">
      <MyButton class="transparent">#архитектура</MyButton>
      <MyButton class="transparent">#комплексная застройка</MyButton>
      <MyButton class="transparent">#интерьеры</MyButton>
      <MyButton class="transparent">#3D, VR, видео</MyButton>
      <MyButton class="transparent">#предметная визуализация</MyButton>
      <MyButton class="transparent">#генплан</MyButton>
      <MyButton class="transparent">#благоустройство</MyButton>
      <MyButton class="transparent">#анимация</MyButton>
      <MyButton class="transparent">#промышленные объекты</MyButton>
      <MyButton class="transparent">#дополнительные материалы</MyButton>
      <MyButton class="transparent1">сбросить фильтр</MyButton>
    </div>
    <div class="img__block">
      <img class="project__img1" src="/img/project_img1.png" alt="foto" />
      <img class="project__img2" src="/img/project_img2.png" alt="foto" />
      <img class="project__img3" src="/img/project_img3.png" alt="foto" />
      <img class="project__img4" src="/img/project_img4.png" alt="foto" />
      <img class="project__img5" src="/img/project_img5.png" alt="foto" />
      <img class="project__img6" src="/img/project_img6.png" alt="foto" />
    </div>
    <div class="btn__block">
      <MyButton class="transparent">больше проектов</MyButton>
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
.project__container {
  padding: 173px 277px 61px;
  background: #2e2e31;
  color: white;
  display: flex;
  flex-direction: column;
}
.tags__block {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 25px;
}
h2 {
  font-size: 50px;
  color: #efefef;
  padding-bottom: 73px;
}
.img__block {
  display: grid;
  gap: 30px;
  padding: 30px 0 50px;
}
.project__img1 {
  grid-column: 1/2;
  grid-row: 1/2;
}
.project__img2 {
  grid-column: 2/3;
  grid-row: 1/3;
}
.project__img3 {
  grid-column: 1/2;
  grid-row: 2/4;
}
.project__img4 {
  grid-column: 2/3;
  grid-row: 3/4;
}
.project__img5 {
  grid-column: 1/2;
  grid-row: 4/5;
}
.project__img6 {
  grid-column: 2/3;
  grid-row: 4/5;
}
.transparent {
  background-color: rgba(28, 28, 28, 0);
  border: 2px solid #f5f5f5;
  border-radius: 6px;
  padding: 8px 35px 8px 35px;
}
.transparent:hover {
  background-color: #ea4c14;
  border: 2px solid #ea4c14;
}
.transparent1 {
  background-color: rgba(28, 28, 28, 0);
  color: #ea4c14;
  padding: 8px 35px 8px 35px;
}
.btn__block {
  display: flex;
  justify-content: center;
}
</style>
