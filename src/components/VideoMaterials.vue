<template>
  <div class="visual__container">
    <div class="visual__img">
      <img src="/img/visual5.png" alt="building" />
      <img class="icon1" src="/img/icon_big.png" alt="icon" />
    </div>
    <div class="visual__info">
      <h2>3D, VR и видео материалы</h2>
      <p>
        Являются дополнительными услугами к любому из основных видов
        визуализации
      </p>
      <div class="visual__items">
        <div class="visual__item">
          <img class="icon" src="/img/icon1.png" alt="icon" />
          <p>VR и 3D виртуальные туры</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon2.png" alt="icon" />
          <p>3D облет 360°</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon3.png" alt="icon" />
          <p>3D видео туры</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon4.png" alt="icon" />
          <p>Анимация</p>
        </div>
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
<style scoped>
.visual__container {
  background: #2e2e31;
  color: white;
  display: flex;
  flex-direction: row;
}
.visual__img {
  position: relative;
}
img {
  width: 859px;
  height: auto;
}
.visual__info {
  display: flex;
  flex-direction: column;
  padding: 82px 277px 0 80px;
  gap: 40px;
}
.visual__items {
  padding: 70px 0 35px;
}
.visual__item {
  display: flex;
  flex-direction: row;
  padding: 35px 0 35px;
  border-bottom: 1px solid #9da0a3;
  justify-content: space-between;
  align-items: center;
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
.icon {
  max-width: 100%;
  width: auto;
  height: 70px;
}
.icon1 {
  width: 286px;
  height: 250px;
  position: absolute;
  top: 45%;
  left: 35%;
}
@media (width < 480px) {
  .visual__container {
    background: #2e2e31;
    color: white;
    display: flex;
    flex-direction: column;
  }
  h2 {
    font-size: 36px;
  }
  .icon1 {
    width: 100px;
    height: 70px;
    position: absolute;
    top: 45%;
    left: 35%;
  }
  .visual__info {
    display: flex;
    flex-direction: column;
    padding: 18px 20px 43px;
    gap: 40px;
  }
  .icon {
    max-width: 100%;
    width: auto;
    height: 50px;
  }
}
</style>
