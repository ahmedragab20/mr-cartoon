<template>
  <div class="app">
    <nav-bar />
    <banner />
    <personalinfo />
    <poster-one />
    <poster-two />
    <cards />
    <mian-poster />
    <poster-three />
    <poster-four />
    <application />
    <main-footer />
  </div>
</template>

<script>
import NavBar from "./components/navBar.vue";
import Banner from "./components/banner.vue";
import Personalinfo from "./components/personalinfo.vue";
import PosterOne from "./components/posterOne.vue";
import PosterTwo from "./components/posterTwo.vue";
import Cards from "./components/cards.vue";
import mianPoster from "./components/mainPoster.vue";
import posterThree from "./components/posterThree.vue";
import posterFour from "./components/posterFour.vue";
import application from "./components/application.vue";
import MainFooter from "./components/mainFooter.vue";
export default {
  name: "App",
  components: {
    NavBar,
    Banner,
    Personalinfo,
    PosterOne,
    PosterTwo,
    Cards,
    mianPoster,
    posterThree,
    posterFour,
    application,
    MainFooter,
  },
};
</script>

<style lang="scss">
// the imports
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css");
@import url("https://fonts.googleapis.com/css2?family=Fira+Sans&display=swap");
// global designs
* {
  font-family: "Fira Sans", sans-serif;
}

html,
body {
  overflow-x: hidden;
}
</style>
