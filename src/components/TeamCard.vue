<template>
  <div class="card">
    <img :src="imageUrl" alt="foto" />
    <p>{{ text }}</p>
    <p>{{ text1 }}</p>
  </div>
</template>
<script>
export default {
  props: {
    text: String,
    text1: String,
    imageUrl: String,
  },
};
</script>
<style scoped>
.card {
  padding: 53px 76px;
  width: 319px;
  height: 501px;
  border-radius: 5px;
  border: solid 3px #464646;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 22px;
  font-size: 22px;
}

img {
  max-width: 100%;
  width: auto;
  height: 70px;
}
</style>
