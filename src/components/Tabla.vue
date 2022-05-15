<template>
<div class="container mt-4">
<table class="table" >
  <thead>
    <tr>
      <th scope="col">Nombre</th>
      <th scope="col">Apellido</th>
      <th scope="col">Fecha de nacimiento</th>
      <th scope="col">Edad</th>
    </tr>
  </thead>
  <tbody>
    <tr v-for="item in usuarios" :key="item">
      <td>{{item.nombre}}</td>
      <td>{{item.apellido}}</td>
      <td>{{item.fechadenacimiento}}</td>
      <td>{{item.edad}}</td>
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
        usuarios : [{
             nombre : 'Miguel',
             apellido : 'Fernández',
             fechadenacimiento : '16/12/1999',
             edad : 23,
            },
            
            {
             nombre : 'Claudia',
             apellido : 'Perez',
             fechadenacimiento : '17/02/1987',
             edad : 35,
            },
           
           {
             nombre : 'Ignacia',
             apellido : 'Olivares',
             fechadenacimiento : '04/09/2011',
             edad : 10,
            }
        ],
      }
    },
  };

</script>

<style></style>