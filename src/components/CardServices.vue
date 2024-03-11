<template>
  <div class="card">
    <img :src="imageUrl" alt="icons" />
    <p>{{ text }}</p>
  </div>
</template>
<script>
export default {
  props: {
    text: String,
    imageUrl: String,
  },
};
</script>
<style scoped>
.card {
  padding: 53px 76px;
  width: 436px;
  height: 180px;
  border-radius: 5px;
  border: solid 3px #464646;
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 22px;
  font-size: 22px;
}
.card:hover {
  cursor: pointer;
  border: solid 3px #ea4c14;
}
img {
  max-width: 100%;
  width: auto;
  height: 70px;
}
</style>
