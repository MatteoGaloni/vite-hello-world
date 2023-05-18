<script>
export default {
    name: "NewComponent",      
      
    data() {
        return {
            
        }
    },
    methods: {
        addbutton() {
    console.log("CIAO")
}
        
    }
}

</script>


<template>
    <h1>PROVA GENERALE SUPREMA</h1>
    <h2>La mia prima app con Vite!</h2>
    <button @click="addbutton()">CLICCAMI</button>
</template>
