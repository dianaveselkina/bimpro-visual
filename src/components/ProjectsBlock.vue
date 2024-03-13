<template>
  <div class="project__container">
    <h2>Какие проекты мы уже реализовали?</h2>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
    <MyButton class="transparent">Оставить заявку</MyButton>
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
.project__container {
  padding: 173px 277px 61px;
  background: #2e2e31;
  color: white;
  display: flex;
  flex-direction: column;
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
</style>
