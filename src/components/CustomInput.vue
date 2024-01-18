<template>
    <div>
      <input v-model="userInput" placeholder="Ingrese un mensaje o texto por favor" size="29">
      <p>{{ userInput }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        userInput: ''
      };
    }
  }
  </script>
  
  <style scoped>
  .custom-input {
    max-width: 300px;
    margin: auto;
    text-align: center;
  }
  
  .input-field {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    box-sizing: border-box;
  }
  
  /* Estilos adicionales según sea necesario */
  </style>