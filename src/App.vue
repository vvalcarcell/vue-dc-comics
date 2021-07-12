<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <BlueRibbon />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import BlueRibbon from "./components/BlueRibbon.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    BlueRibbon,
  },
};
</script>

<style lang="scss">
@import "./style/colors.scss";
</style>
