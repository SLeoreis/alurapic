<template>
<div>
  <h1>{{titulo}}</h1>
  <img src="{{ foto.url }}" alt= "{{ foto.titulo }}">
</div>
</template>

<script>
export default {
    data() {
        return {
            titulo: 'AluraPic',
            foto: {
                url: 'https://love.doghero.com.br/wp-content/uploads/2018/03/shutterstock_154829555-1024x680.webp',
                titulo: 'Cachorro'
            }
        }
    }
}
</script>

<style>

</style>
