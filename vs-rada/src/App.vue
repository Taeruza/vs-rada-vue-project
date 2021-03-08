<template>
  <div id="app">
    <div class="bg-container">
      <Navbar />
      <b-container fluid>
        <b-row>
          <b-col>
            <Navigation />
          </b-col>
          <b-col cols="9">
            <router-view/>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Navigation
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

.bg-container {
  background: #f8f8f8;
  height: 2000px;
}
</style>
