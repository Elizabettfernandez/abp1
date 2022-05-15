<template>
 <div class="container">
  <h1>Lista de usuarios</h1>
 <Tabla/>
</div>
</template>


<script>
import Tabla from '@/components/Tabla.vue'
export default {
  name: "HomeView",
  components: {
    Tabla
  },
};
</script>
 



<style>
h1{
  text-align: center;
}
</style>