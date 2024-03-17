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
.calculation {
  font-size: 55px;
  color: #fff;
  text-align: center;
}
.transparent {
  padding: 20px 123px;
}
</style>
