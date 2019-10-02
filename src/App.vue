<template>
  <div id="app">
    <Header></Header>
    <AppBody></AppBody>
  </div>
</template>
<style scoped lang="scss">
@import "assets/colors.scss";
#app{
  background-image: $background-image !important;
  size: $size !important;
  background-repeat: $backgroud-repeat !important;
  overflow: $overflow !important;
  height: $height !important;
  max-height: $max-height !important;
}
</style>
<script>
import Header from "router/frame/Header.vue";
import AppBody from "router/frame/Body.vue";
export default {
  name: "app",
  components: {
    Header,
    AppBody
  }
};
</script>


