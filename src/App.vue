<template>
  <NavbarComponent/>
  <BackgroundComponent />
  <br>
  <AboutMeComponent />

</template>

<script>
import NavbarComponent from './components/NavbarComponent.vue'
import BackgroundComponent from './components/BackgroundComponent.vue'
import AboutMeComponent from "./components/AboutMeComponent.vue";


export default {
  name: 'App',
  components: {
    NavbarComponent,
    BackgroundComponent,
    AboutMeComponent,
  }
}
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
