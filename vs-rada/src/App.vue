<template>
  <div id="app">
    <Navbar />
    <b-container fluid>
      <b-row class="text-center">
        <b-col></b-col>
        <b-col cols="9">
          <router-view/>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
  font-family: Georgia, 'Times New Roman', Times, serif, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #165696;
}
</style>
