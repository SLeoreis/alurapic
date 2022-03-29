<template>
<div>
  <h1>{{titulo}}</h1>
  <img  v-bind:scr="foto.url" v-bind:alt="foto.titulo">
</div>
</template>

<script>
export default {
    data() {
        return {
            titulo: 'AluraPic',
            foto: {
                url: 'https://ultramacho.com.br/wp-content/uploads/2020/08/cachorro.jpg',
                titulo: 'Cachorro'
            }
        } 
    }
}
</script>

<style>

</style>
