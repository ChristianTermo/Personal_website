<template>
  <div v-if="!isMobile()">
    <NavbarComponent />
    <BackgroundComponent />
    <br />
    <AboutMeComponent />
  </div>
  <div v-else>
    <SidebarComponent />
    <br />
    <AboutMeComponent />
  </div>
</template>

<script>
import NavbarComponent from "./components/NavbarComponent.vue";
import BackgroundComponent from "./components/BackgroundComponent.vue";
import AboutMeComponent from "./components/AboutMeComponent.vue";
import SidebarComponent from "./components/SidebarComponent.vue";
export default {
  name: "App",
  components: {
    NavbarComponent,
    BackgroundComponent,
    AboutMeComponent,
    SidebarComponent,
  },
  methods: {
    isMobile() {
      if (
        /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(
          navigator.userAgent
        )
      ) {
        return true;
      } else {
        return false;
      }
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
