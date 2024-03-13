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
  padding: 8px 35px 30px 35px;
  cursor: pointer;
  background-color: #ea4c14;
  font-size: 18px;
  color: fff;
  border-radius: 6px;
}
</style>
