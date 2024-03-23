<template>
    <h3>{{ counter }}</h3>
    <button @click="addCounter">Incrementar</button>
</template>


<script lang="ts">
//estructura option API
    import{ defineComponent} from "vue";
    export default defineComponent({
        name: 'CounterOption',
        component:{},
        data(){
            let counter = 0;
            return {counter}
        },
        methods: {
            addCounter(){
                this.counter++
               //this solo se usa en optionAPI para referirse a los datos
            }
        },
    })
</script>

<style scoped>
</style>