<template>
  <div class="app">
    <a href="#" class="to-top">Top</a>
    <nav-bar />
    <banner />
    <personalinfo />
    <poster-one />
    <cards />
    <poster-two />
    <application />
    <main-footer />
  </div>
</template>

<script>
import NavBar from "./components/navBar.vue";
import Banner from "./components/banner.vue";
import Personalinfo from "./components/personalinfo.vue";
import PosterOne from "./components/posterOne.vue";
import Cards from "./components/cards.vue";
import posterTwo from "./components/posterTwo.vue";
import application from "./components/application.vue";
import MainFooter from "./components/mainFooter.vue";
export default {
  name: "App",
  components: {
    NavBar,
    Banner,
    Personalinfo,
    PosterOne,
    Cards,
    posterTwo,
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

.app {
  position: relative;

  .to-top {
    width: 35px;
    height: 35px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.75rem;
    position: fixed;
    right: 30px;
    bottom: 30px;
    color: #fff;
    background-color: #111;
    border-radius: 5px;
    opacity: 0;
    pointer-events: none;
    transition: 0.3s;

    &.active {
      opacity: 1;
      pointer-events: all;
    }
  }
}
</style>
