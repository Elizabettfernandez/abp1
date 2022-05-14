<template>
<div class="container mt-4">
  <h1>Tabla de usuarios</h1>
<table class="table">
  <thead>
    <tr>
      <th scope="col">N°</th>
      <th scope="col">Nombre</th>
      <th scope="col">Apellido</th>
      <th scope="col">Fecha de nacimiento</th>
      <th scope="col">Edad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>{{this.usuarios.nombre}}</td>
      <td>{{this.usuarios.apellido}}</td>
      <td>{{this.usuarios.fechadenacimiento}}</td>
      <td>{{this.usuarios.edad}}</td>
    </tr>
  </tbody>
</table>
</div>
</template>


<script>
export default {
  name: 'Tabla',
      data(){
        return {
        usuarios : 
          {
             nombre : 'Miguel',
             apellido : 'Fernández',
             fechadenacimiento : '16/12/1999',
             edad : 23,
            },
        }  
      },
      
};

</script>

<style>
h1{
  text-align: center;
}
</style>