<template>
  <div class="benefit_container">
    <div class="benefit__items">
      <hr />
      <div class="benefit__item">
        <p class="orange">Скидка до 50 %</p>
        <p class="white">при заказе от 20 000м2</p>
      </div>
      <hr />
      <div class="benefit__item">
        <p class="orange">Скидка до 5 %</p>
        <p class="white">на последующие заказы</p>
      </div>
      <hr />
      <div class="benefit__item">
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
<style>
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
  padding: 20px 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 5px;
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
</style>
