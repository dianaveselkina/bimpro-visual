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
      <MyButton class="communication__btn">Получить консультацию</MyButton>
      <p>
        Нажав на кнопку, я соглашаюсь на&nbsp;обработку
        <span>персональных данных</span>
      </p>
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
    background: #222224;
    padding: 15px 20px;
  }
  .calculation,
  .transparent {
    display: none;
  }
  .communication__container-mobil {
    background: #2e2e31;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    max-width: 480px;
    height: auto;
    padding: 56px 20px;
  }
  h2 {
    font-size: 48px;
    text-align: center;
  }
  .form {
    margin: 41px 0 30px;
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  input {
    padding: 16px;
    border-radius: 6px;
    font-family: inherit;
    font-size: inherit;
    color: inherit;
    background-color: transparent;
  }
  .communication__btn {
    padding: 19px 45px;
    max-width: 340px;
    margin: 0 auto;
  }
  p {
    font-size: 24px;
    padding: 40px 0 56px;
    text-align: center;
  }
  span {
    font-size: 24px;
    color: #ea4c14;
  }
}
</style>
