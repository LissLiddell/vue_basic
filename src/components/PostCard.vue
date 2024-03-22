<template>
    <div class="post-card">
    <h3> Soy un título </h3>
    <p>Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500</p>
    </div>
    <!-- Se pinta el componente en el template que se invoco en el script-->
    <PostButton/>
</template>

<script lang ="ts" setup>
    import PostButton from './PostButton.vue';

</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid plum;
}
</style>