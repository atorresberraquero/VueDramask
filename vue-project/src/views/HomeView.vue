<script setup lang="ts">
import obras from "../App.vue"
import Card from '../components/Card.vue'
import ObrasDisplay from "../components/ObrasDisplay.vue"
</script>

<template>
    <br><br><br>
    Vista Home

    <section class="menu" id="menu">

<h1 class="heading"> Proximos <span>estrenos</span> </h1>

<!-- <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav> -->

</section>


    <ObrasDisplay>

    </ObrasDisplay>

</template>

<style scoped>
.heading {
  text-align: center;
  color: #000000;
  text-transform: uppercase;
  padding-bottom: 3.5rem;
  font-size: 4rem;
}
.heading span {
  color: #F0D303;
  text-transform: uppercase;
}


</style>