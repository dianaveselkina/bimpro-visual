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
    <div class="ihfo__block">
      <h2 class="info__title">Слово руководителя</h2>
      <div class="info__wrapper">
        <div class="info__text">
          <p class="info__text1">
            Мы знаем, как важно наличие качественных визуализаций для реализации
            недвижимости в современном мире, поэтому делаем продукт в полном
            соответствии с высоким стандартом, что помогает повысить
            привлекательность проекта и привлечь новых клиентов на популярных
            площадках.
          </p>
          <p class="info__text1">
            Вдыхаем жизнь в каждый рендер и даем возможность потребителю увидеть
            объект еще до его реализации - это то, что мы по настоящему любим и
            умеем.
          </p>
        </div>
        <div class="info__line"></div>
        <div class="info__foto">
          <div class="foto__director">
            <img src="/img/project_img7.png" alt="foto" />
          </div>
          <p class="foto__description">
            <span>МАКСИМ НИКИТИН</span><br />Ведущий визуализатор
          </p>
        </div>
      </div>
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
.info__title {
  padding-top: 123px;
}
.info__line {
  background-color: #ea4c14;
  height: 195px;
  width: 1px;
  margin: 0 90px;
}
.info__wrapper {
  display: flex;
  flex-direction: row;
  align-items: center;
}
.info__foto {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}
.foto__director {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  background-color: #d9d9d9;
}

.info__text1 {
  margin: 60px 0 22px;
  font-size: 18px;
}
.foto__description {
  text-align: center;
}
@media (width < 480px) {
  .project__container {
    padding: 0 20px;
    background: #2e2e31;
  }
  .tags__block {
    display: none;
  }
  .img__block {
    display: flex;
    flex-direction: column;
  }
  .project__img2,
  .project__img2 {
    width: 280px;
    height: 350px;
  }
  h2 {
    font-size: 31px;
    text-transform: uppercase;
    text-align: center;
  }
  .ihfo__block {
    display: none;
  }
}
</style>
