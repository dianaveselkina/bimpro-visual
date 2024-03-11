<template>
  <div class="steps__container">
    <h2><span>5 шагов </span>работы с нами</h2>
    <div class="steps__items">
      <div class="step__item">
        <p class="number">1</p>
        <p class="orange">Оставьте</p>
        <p class="white">заявку</p>
      </div>
      <div class="step__item num">
        <img src="img/arrow.png" alt="arrow" />
      </div>
      <div class="step__item">
        <p class="number">2</p>
        <p class="orange">Получите</p>
        <p class="white">
          бесплатный расчет<br />
          стоимости и сроков
        </p>
      </div>
      <div class="step__item num">
        <img src="/img/arrow.png" alt="arrow" />
      </div>
      <div class="step__item">
        <p class="number">3</p>
        <p class="orange">Заключите договор</p>
        <p class="white">и внесите аванс</p>
      </div>
      <div class="step__item num">
        <img src="/img/arrow.png" alt="arrow" />
      </div>
      <div class="step__item">
        <p class="number">4</p>
        <p class="orange">Мы разработаем</p>
        <p class="white">визуализации</p>
      </div>
      <div class="step__item num">
        <img src="/img/arrow.png" alt="arrow" />
      </div>
      <div class="step__item">
        <p class="number">5</p>
        <p class="orange">Получите</p>
        <p class="white">готовые материалы</p>
      </div>
    </div>
    <MyButton class="transparent">Оставить заявку</MyButton>
  </div>
</template>
<script>
import MyButton from './MyButton.vue';
export default {
  components: {
    MyButton,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.steps__container {
  padding: 56px 277px 111px;
  background-color: #222224;
  color: white;
}
h2 {
  text-transform: uppercase;
  font-size: 50px;
  color: #efefef;
}
h2 > span {
  color: #ea4c14;
  text-transform: uppercase;
}
.steps__items {
  padding: 79px 0 82px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.step__item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.num {
  padding-top: 20px;
}
.number {
  font-size: 50px;
  color: #ea4c14;
}
.orange {
  font-size: 22px;
  text-align: center;
  color: #ea4c14;
}
.white {
  font-size: 22px;
  text-align: center;
  color: white;
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
