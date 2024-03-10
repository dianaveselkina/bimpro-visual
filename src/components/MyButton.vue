<template>
  <button class="btn"><slot></slot></button>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {},
};
</script>
<style>
.btn {
  width: 400px;
  height: 70px;
  cursor: pointer;
  background-color: #ea4c14;
  font-size: 18px;
  color: fff;
  border-radius: 6px;
}
</style>
