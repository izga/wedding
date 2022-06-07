<template>
  <div id="app">
    <img alt="Pozivnica" src="./assets/pozivnica.jpeg">
    <p>Molimo potvrdite vaš dolazak: </p>
    <contact-form />
  </div>
</template>

<script>
import ContactForm from './components/ContactForm.vue'

export default {
  name: 'App',
  components: {
    ContactForm
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

img {
  width: 700px;
  padding-bottom: 60px;
}
</style>
