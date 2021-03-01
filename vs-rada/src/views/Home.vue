<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home {
  background: #ffffff;
  box-shadow: 0px 2px 10px 0px #a4a4a454;
  margin-top: 50px;
  margin-right: 50px;
  padding: 50px;
}
</style>
