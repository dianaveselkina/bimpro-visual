<template>
  <div class="visualization__container">
    <div class="visualization__cards">
      <VisualDiv
        imageUrl="/img/visual1.png"
        title="визуализация комплексной застройки"
        text1="Визуализация жилых комплексов"
        text2="Визуализация благоустройства территории"
      />
      <VisualDiv
        class="color"
        imageUrl="/img/visual2.png"
        title="архитектурная визуализация"
        text1="Визуализация жилых зданий"
        text2="Визуализация общественных, промышленных и складских зданий"
      />
      <VisualDiv
        imageUrl="/img/visual3.png"
        title="интерьерная визуализация "
        text1="Визуализация общественных пространств"
        text2="Комплексная визуализация жилых помещений "
      />
      <VisualDiv
        class="color"
        imageUrl="/img/visual4.png"
        title="рекламная и предметная визуализация"
        text1="Визуализация для каталогов мебели, декора, освещения"
      />
      <VisualDiv />
      <VisualDiv />
    </div>
  </div>
</template>
<script>
import VisualDiv from './VisualDiv.vue';

export default {
  components: {
    VisualDiv,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.color {
  border: none;
  background: #222224;
}
</style>
