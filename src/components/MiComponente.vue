<template>
    <div id="mi-componete">
        <h1>Este es mi COMPONETE</h1>
        <small>{{ texto }}</small><br>
        <u><b>{{ textodinamicoentretemplates }}</b></u>
    </div>
</template>
    
<script>
export default {
    name: 'MiComponete',
    props:{
        textodinamicoentretemplates: String
    },
    data(){
        return {
            texto: 'texto desde mi componente'
        }
    }
}
</script>

<style scoped>

</style>