<template>
  <div class="wrapper">
    <HeaderDiv />
    <HeroDiv />
    <ServicesDiv />
    <BenefitDiv />
    <AnimationDiv />
    <ListsDiv />
    <StepsDiv />
    <VisualizationBlock />
    <VideoMaterials />
  </div>
</template>
<script>
import HeaderDiv from './components/HeaderDiv.vue';
import HeroDiv from './components/HeroDiv.vue';
import ServicesDiv from './components/ServicesDiv.vue';
import BenefitDiv from './components/BenefitDiv.vue';
import AnimationDiv from './components/AnimationDiv.vue';
import ListsDiv from './components/ListsDiv.vue';
import StepsDiv from './components/StepsDiv.vue';
import VisualizationBlock from './components/VisualizationBlock.vue';
import VideoMaterials from './components/VideoMaterials.vue';
export default {
  components: {
    HeaderDiv,
    HeroDiv,
    ServicesDiv,
    BenefitDiv,
    AnimationDiv,
    ListsDiv,
    StepsDiv,
    VisualizationBlock,
    VideoMaterials,
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
