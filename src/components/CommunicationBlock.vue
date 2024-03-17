<template>
  <DocketBlock />
  <PartnersBlock />
</template>
<script>
import DocketBlock from './DocketBlock.vue';
import PartnersBlock from './PartnersBlock.vue';

export default {
  components: {
    DocketBlock,
    PartnersBlock,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.services__container {
  padding: 100px 277px;
  background-color: #222224;
  color: white;
}
</style>
