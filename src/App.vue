<template>
  <div class="wrapper">
    <HeaderDiv />
  </div>
</template>
<script>
import HeaderDiv from './components/HeaderDiv.vue';
export default {
  components: {
    HeaderDiv,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
a {
  color: inherit;
  text-decoration: none;
}
ol,
ul {
  list-style: none;
}
img {
  max-width: 100%;
  width: 100%;
  height: auto;
}
button {
  cursor: pointer;
  color: inherit;
  font-family: inherit;
  border: 0;
}
.wrapper {
  max-width: 1920px;
  background-color: #222224;
  margin: 0 auto;
}
</style>
