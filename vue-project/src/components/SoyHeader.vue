<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue';
</script>

<template>

<header class="header">
    <a href="">
      <img src="../assets/logo3.png" alt="" width="50">
    </a>

    <nav class="navbar-header">
      <a href="">Inicio</a>
      <a href="">Cartelera</a>
      <a href="">Proximos estrenos</a>
      <a href="">Sobre Nosotros</a>
    </nav>

</header>
</template>

<style scoped>
.header {
  background-color: #F0D303;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.5rem 7%;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}

.navbar-header{
    align-items: end;
}
.navbar-header a {
  display: inline-block; 
  margin-right: 15px; 
  color: black; 
  font-family: Arial, sans-serif; 
  text-decoration: none; 
}

.navbar-header a:hover {
  text-decoration: underline; 
}


</style>