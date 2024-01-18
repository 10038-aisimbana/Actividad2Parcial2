<template>
  <div id="app">
    <h1 class="title">Actividad 2</h1>
    <p class="info">Nombre: Adrian Simbaña</p>
    <p class="info">14386</p><br>
    <CustomInput v-model="message" />
  </div>
</template>

<script>
import CustomInput from './components/CustomInput.vue';

export default {
  components: {
    CustomInput
  },
  data() {
    return {
      message: 'Mensaje inicial'
    };
  }
}
</script>

<style scoped>
#app {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  margin-top: 20px;
}

.title {
  font-family: 'Arial', sans-serif;
  font-size: 28px;
  margin-bottom: 10px;
}

.info {
  font-family: 'Arial', sans-serif;
  font-size: 16px;
  margin: 5px 0;
}
</style>
