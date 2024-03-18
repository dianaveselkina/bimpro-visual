<template>
  <div class="animation__container">
    <div class="animation__wrapper">
      <div class="animation__info">
        <div class="animation__percent">
          <div class="percent">
            <div class="percent__counter">
              <p class="num">+</p>
              <div class="counter">
                {{ counter }}
              </div>
            </div>
            <p class="percent1">%</p>
            <div class="percent__band">
              <transition name="band">
                <div class="band__orange"></div>
              </transition>
            </div>
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
export default {
  data() {
    return {
      counter: 0,
    };
  },
  mounted() {
    setInterval(() => {
      this.counter++;
    }, 1000);
  },
};
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
.percent__counter {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 12px;
  font-size: 40px;
  position: absolute;
  bottom: 0;
  left: 0;
}
.percent1 {
  position: absolute;
  bottom: 18px;
  right: 8px;
  font-size: 32px;
}
.num {
  color: #ea4c14;
  font-size: 70px;
  font-weight: bold;
}
.counter {
  color: #ea4c14;
  font-size: 100px;
  font-weight: bold;
}
.percent__band {
  position: absolute;
  top: 0;
  right: 0;
  width: 44px;
  height: 212px;
  border: solid 3px #ea4c14;
}
.band__orange {
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: #4d14ea;
  width: 38px;
  height: 1px;
}
.animation__title {
  padding-left: 276px;
  font-size: 40px;
  text-transform: uppercase;
}

.band-enter-active,
.band-leave-active {
  transition: all 1s ease-out;
}
.band-enter,
.band-leave-to {
  transform: scale(8);
  opacity: 1;
}
</style>
