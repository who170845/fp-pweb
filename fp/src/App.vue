<!-- <template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/RegistrationForm.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
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
</style> -->

<template>
  <div id="app">
    <RegistrationPage />
  </div>
</template>

<script>
import RegistrationPage from './components/RegistrationPage.vue';

export default {
  components: {
    RegistrationPage,
  },
};
</script>

<style>
/* Gaya umum aplikasi Anda di sini */
</style>
