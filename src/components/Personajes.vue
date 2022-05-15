<template>
<div class="container mt-5 mb-5">
    <div class="card shadow" style="max-width: 18rem" display flex>
    <div class="card-body" v-for="item in personajes" :key="item.id">
    <h5 class="card-title">{{item.nombre}}</h5>
    <p class="card-text">{{item.descripcion}}</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
</div>
</template>

<script>
export default {
    name: 'Personajes',
    data(){
        return {
        personajes:[
            {
            "id": "1",
            "nombre": "pikachu",
            "descripcion": "lorem ipsum uhiuhiuhihoi"
            },
            {
            "id": "2",
            "nombre": "kakuna",
            "descripcion": "lorem ipsum uhiuhiuhihoi"
            },
            {
            "id": "3",
            "nombre": "beedrill",
            "descripcion": "lorem ipsum uhiuhiuhihoi"
            },
            {
            "id": "4",
            "nombre": "metapod",
            "descripcion": "lorem ipsum uhiuhiuhihoi"
            },
            {
            "id": "5",
            "nombre": "rattata",
            "descripcion": "lorem ipsum uhiuhiuhihoi"
            }
        ]
    };


    }

}
</script>

<style>
.container{
    margin-bottom: 5px;
}
</style>