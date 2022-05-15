<template>
 <div class="container">
  <h1>Lista de usuarios</h1>
 <Tabla/>
 <h2>Cards de personajes</h2>
 <Personajes />
</div>
</template>


<script>
import Tabla from '@/components/Tabla.vue';
import Personajes from '@/components/Personajes.vue'

export default {
  name: "HomeView",
  components: {
    Tabla,
    Personajes
  },
};
</script>
 



<style>
h1{
  text-align: center;
}
</style>