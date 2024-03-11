<template>
  <div class="lists__container">
    <div class="list__items">
      <div class="list__item">
        <p><span>как</span> мы поможем вашему бизнесу</p>
      </div>
      <hr class="hr" />
      <div class="list__item">
        <p><span>кому</span> наши решения помогут</p>
      </div>
      <hr class="hr" />
      <div class="list__item">
        <p><span>подробнее</span> о нашей работе</p>
      </div>
    </div>
    <div class="lists__description">
      <div class="list__item">
        <p class="description">Снизить количество ошибок</p>
      </div>
      <hr class="hr1" />
      <div class="list__item">
        <p class="description">Согласовать проект с заказчиком</p>
      </div>
      <hr class="hr1" />
      <div class="list__item">
        <p class="description">Повысить привлекательность проекта</p>
      </div>
      <hr class="hr1" />
      <div class="list__item">
        <p class="description">Выделиться на фоне конкуррентов</p>
      </div>
      <hr class="hr1" />
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.lists__container {
  padding: 100px 277px;
  background-color: #222224;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  gap: 166px;
}
.list__items {
  display: flex;
  flex-direction: column;
}
p {
  font-size: 50px;
  color: #ea4c14;
}
p > span {
  color: white;
}
.hr {
  margin: 46px 0;
  border: 0.5px solid #e3e2e2;
  width: 486px;
  height: 0px;
  opacity: 0.2;
}
.hr1 {
  border: 0.5px solid #9da0a3;
  width: 784px;
  height: 0px;
  opacity: 0.3;
}
.description {
  padding: 30px 0;
  font-size: 22px;
  line-height: 123%;
  letter-spacing: 0.01em;
  color: #ea4c14;
}
</style>
