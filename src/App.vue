<template>
<Portafolio></Portafolio>
</template>

<script setup>
import Portafolio from './components/Portafolio.vue'
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e80606;
  margin-top: 60px;
  background-image: url('./assets/mortal-kombat-11-logo-dragon_3840x2160_xtrafondos.com.jpg');
  background-size: cover; /* Ajusta el tamaño de la imagen para cubrir todo el contenedor */
  background-position: center; /* Centra la imagen de fondo */
  background-attachment: fixed; /* Fija la imagen de fondo para que no se mueva */
}
</style>
