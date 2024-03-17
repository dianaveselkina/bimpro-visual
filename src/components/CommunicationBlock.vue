<template>
  <DocketBlock />
  <PartnersBlock />
  <MediaBlock />
  <NewsBlock />
</template>
<script>
import DocketBlock from './DocketBlock.vue';
import PartnersBlock from './PartnersBlock.vue';
import MediaBlock from './MediaBlock.vue';
import NewsBlock from './NewsBlock.vue';

export default {
  components: {
    DocketBlock,
    PartnersBlock,
    MediaBlock,
    NewsBlock,
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
