<template>
 <div id="app">
  <b-container>  
<HomeView />
  </b-container>
 </div>
</template>


<script>
  import HomeView from "./views/HomeView.vue"
  
  export default {
    name: "App",
    components: {
      HomeView
  }
  };
  
</script>

<style></style>
