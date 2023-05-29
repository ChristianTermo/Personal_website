<template>
  <nav class="navbar fixed-top bg-dark" data-bs-theme="dark">
    <div class="divide">
      <div class="d-flex">
        <a href="#mission">
          <button class="btn-hover color-8">Mission</button></a
        >
        <a href="#aboutme"
          ><button class="btn-hover color-8">About me</button></a
        >
        <label for="" >{{fontSize}}</label>
        <a href="#tecnologie"
          ><button class="btn-hover color-8">Tecnologie</button></a
        >
        <a href="#contatti"
          ><button class="btn-hover color-8">Contatti</button></a
        >
        <a href="https://calendly.com/christiantermo"
          ><button class="btn-hover color-8">Fissa una call</button></a
        >
      </div>
    </div>
  </nav>
</template>

<script setup>
/*import {ref} from 'vue'

let details = navigator.userAgent;
let regexp = /android|iphone|kindle|ipad/i;
let isMobileDevice = regexp.test(details);

let fontSize = ref(1);

if (isMobileDevice) {
  fontSize = 1;
  alert('its pikachu');
} else {
  fontSize = 1;
}*/
</script>

<style scoped>

@import "../css/navbar.css";
  .btn-hover {
 /*font-size: v-bind(fontSize);*/
  }
   
</style>

