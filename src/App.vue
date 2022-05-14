<template>
<!-- <div class="container mt-3">
  <div class="grid">
    <div class="row">
      <div class="col">
        <p class="h3 text-success fw-bold">Lista de usuarios</p>
          
        </div>
      </div>
    </div>
 </div> -->


<Tabla/>
</template>


<script>
  import Tabla from './components/Tabla.vue'
  
  export default {
  name: 'App',
  components: {
    Tabla
  }
  };
  
</script>

<style>

</style>
