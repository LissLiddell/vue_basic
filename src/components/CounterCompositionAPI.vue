<template>
    <h3>{{ counter }}</h3>
    <button @click="addCounter"> Incrementar</button>
</template>



<script lang="ts" setup >
// setup te ahorra el define component, name and setup
//se programa en javascript y luego se agrega los tipos de datos que usa typescript
//en composition cuando un valor "reaccione" a los cambios se marca como referecnia - Ref, ref (linea 13 y 14)
// SOLO con typeScript se usa Ref para especificar el tipo de dato
    import {  Ref, ref } from "vue";
            let counter:Ref = ref(0)
            const addCounter = ():void => {
                counter.value++
            }

// import {  Ref, ref } from "vue";
   // export default defineComponent({
     // name: 'CounterComposition',
     //   setup(){
          //  let counter:Ref = ref(0)
          //  const addCounter = ():void => {
            //    counter.value++
               // console.log(counter)
        //    }j
  //          return {counter, addCounter}
  //    }  
 //   })
</script>