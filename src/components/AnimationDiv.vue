<template>
  <div class="animation__container">
    <div class="animation__wrapper">
      <div class="animation__info">
        <div class="animation__percent">
          <div class="percent">
            <div class="percent__band"></div>
          </div>
        </div>
        <p>
          *По данным ГК «Первый Трест» № 12 среди российских застройщиков в
          рейтинге ЕРЗ, клиент «БИМПРО»
        </p>
      </div>
      <h2 class="animation__title">
        Визуализированная недвижимость продается на 20% быстрее!
      </h2>
    </div>
    <img src="/img/animation_img.png" alt="building" />
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.animation__container {
  background-color: #171719;
  color: white;
  display: flex;
  flex-direction: row;
}
.animation__info {
  padding: 60px 114px 60px 276px;
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  gap: 15px;
}
.percent {
  position: relative;
  width: 208px;
  height: 218px;
  border: solid 3px #ffffff;
}
.percent__band {
  position: absolute;
  top: 0;
  right: 0;
  width: 44px;
  height: 218px;
  border: solid 3px #ea4c14;
}
.animation__title {
  padding-left: 276px;
  font-size: 40px;
  text-transform: uppercase;
}
</style>
