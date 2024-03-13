<template>
  <div class="visualization__container">
    <div class="visualization__cards">
      <VisualDiv
        imageUrl="/img/development_img.png"
        title="визуализация комплексной застройки"
        text1="Визуализация жилых комплексов"
        text2="Визуализация благоустройства территории"
      />
      <VisualDiv />
      <VisualDiv />
      <VisualDiv />
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
<style scoped></style>
