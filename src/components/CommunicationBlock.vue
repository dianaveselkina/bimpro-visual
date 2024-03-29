<template>
  <DocketBlock />
  <PartnersBlock />
  <MediaBlock />
  <NewsBlock />
  <div class="communication__container">
    <p class="calculation">
      получите расчет стоимости вашего проекта в день заявки
    </p>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <div class="communication__container-mobil">
      <h2>Оставьте заявку на звонок</h2>
      <form class="form">
        <input
          class="create__input"
          type="text"
          name="name"
          placeholder="Имя"
        />
        <input
          class="create__input"
          type="tel"
          name="phone"
          placeholder="Телефон"
        />
      </form>
      <MyButton class="hero__btn">Рассчитать стоимость проекта</MyButton>
    </div>
  </div>
</template>
<script>
import DocketBlock from './DocketBlock.vue';
import PartnersBlock from './PartnersBlock.vue';
import MediaBlock from './MediaBlock.vue';
import NewsBlock from './NewsBlock.vue';
import MyButton from './MyButton.vue';

export default {
  components: {
    DocketBlock,
    PartnersBlock,
    MediaBlock,
    NewsBlock,
    MyButton,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.communication__container {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 51px;
  padding: 100px 277px;
  background-color: #2e2e31;
  color: white;
}
.communication__container-mobil {
  display: none;
}
.calculation {
  font-size: 55px;
  color: #fff;
  text-align: center;
}
.transparent {
  padding: 20px 123px;
}
@media (width < 480px) {
  .communication__container {
    background: #2e2e31;
    padding: 15px 20px;
  }
  .calculation,
  .transparent {
    display: none;
  }
  .communication__container-mobil {
    display: block;
    max-width: 480px;
    height: auto;
  }
  h2 {
    font-size: 48px;
    text-align: center;
  }
  .form {
    display: flex;
    flex-direction: column;
  }
}
</style>
