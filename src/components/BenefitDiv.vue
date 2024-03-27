<template>
  <div class="benefit_container">
    <div class="benefit__items">
      <hr />
      <div
        class="benefit__item"
        data-title="Размер скидки зависит от объема проекта и устанавливается индивидуально при расчете коммерческого предложения"
      >
        <p class="orange">Скидка до 50 %</p>
        <p class="white">при заказе от 20 000м2</p>
      </div>
      <hr />
      <div
        class="benefit__item"
        data-title="На второй и последующие заказы вы получите дополнительную скидку 5%."
      >
        <p class="orange">Скидка до 5 %</p>
        <p class="white">на последующие заказы</p>
      </div>
      <hr />
      <div
        class="benefit__item"
        data-title="Срок исполнения зависит от сложности задачи, размера проекта и рассчитывается индивидуально"
      >
        <p class="orange">5 рабочих дней</p>
        <p class="white">средний срок исполнения</p>
      </div>
      <hr />
      <div class="benefit__item">
        <p class="orange">бесплатная консультация</p>
        <p class="white">по любым вопросам</p>
      </div>
      <hr />
    </div>
    <hr class="hr-line" />
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.benefit_container {
  padding: 56px 277px;
  background-color: #222224;
  color: white;
}
.benefit__items {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.benefit__item {
  position: relative;
  padding: 20px 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 5px;
}
.benefit__item:hover::after {
  content: attr(data-title);
}
.benefit__item:hover::after {
  content: attr(data-title);
  width: 262px;
  height: 101px;
  position: absolute;
  left: 20%;
  top: 30%;
  z-index: 1;
  background: rgba(0, 0, 0, 0.8);
  border-radius: 10px;
  color: 9DA0A3;
  font-size: 18px;
  padding: 20px;
}
.hr-line {
  padding: 0;
  height: 0;
  border: none;
  border-top: 1px solid #9b9b9b;
}
.orange {
  font-size: 18px;
  color: #ea4c14;
  text-transform: uppercase;
}
.white {
  font-size: 18px;
  color: white;
  text-transform: uppercase;
}
@media (width < 480px) {
  .benefit_container {
    padding: 43px 20px 79px;
    background: #2e2e31;
  }
  .benefit__items {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
}
</style>
