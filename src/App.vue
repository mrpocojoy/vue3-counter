<script>

  export default {
    data: () => ({
      contador: 200,
    }),
    methods: {
      incrementar() {   this.contador++;   },
      disminuir()   {   this.contador--;   },
      resetear()    {   this.contador = 10;   },
    },
    
    
  };


</script>


<template>

  <div class="container">
    <img src="./assets/logo.svg" alt="" width="125" height="125"/>
    <h1>Hola Mundo desde VUEJS3</h1>
    <hr />
    <h2>Contador: {{ contador }}</h2>
    <button @click="incrementar()">+1</button>
    <button @click="disminuir()">-1</button>
    <button @click="resetear()">Reset</button>
  </div>

</template>
