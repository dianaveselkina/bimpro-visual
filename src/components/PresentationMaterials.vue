<template>
  <div class="visual__container">
    <img src="/img/visual6.png" alt="building" />
    <div class="visual__info">
      <h2>дополнительные презентационные материалы</h2>
      <p>
        Являются дополнительными услугами к любому из основных видов
        визуализации
      </p>
      <div class="visual__items">
        <div class="visual__item">
          <img class="icon" src="/img/icon5.png" alt="icon" />
          <p>Планировочные схемы</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon6.png" alt="icon" />
          <p>3Визуализация генплана</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon7.png" alt="icon" />
          <p>Визуализация фасадов</p>
        </div>
        <div class="visual__item">
          <img class="icon" src="/img/icon8.png" alt="icon" />
          <p>Композиции с материалами</p>
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
  background: #222224;
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
  padding: 56px 0 35px;
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
  .transparent {
    margin: 0 auto;
  }
}
</style>
