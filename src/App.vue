<template>
  <div id="app">
    <Header />
    <Main />
    <BlueRibbon />
    <Footer />
    <BottomBar />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import BlueRibbon from "./components/BlueRibbon.vue";
import BottomBar from "./components/BottomBar.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    BlueRibbon,
    BottomBar,
  },
};
</script>

<style lang="scss">
@import "./style/app.scss";
</style>
