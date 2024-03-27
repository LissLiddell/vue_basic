 <!--  <template>
aqui va codigo html , etiquetas,div,input,h1                      VISTA
</template> --> 

<!-- <script lang="ts" lang ts indica que se usa type script> 
Logica, datos, funcionamientoj                                    MODELO
</script>-->

<!-- <style>
estilos                                                           ESTILOS
</style>-->
<template>
  <CounterCompositionAPI />
  <CounterCompositionAPI />
  <CounterCompositionAPI />
</template>


<script lang="ts" setup>
//   import CounterOptionAPI from'./components/CounterOptionAPI.vue'
   import CounterCompositionAPI from'./components/CounterCompositionAPI.vue' 
</script>

<style>
h1 {
  color:purple;
}
</style>


<!--
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
-->
