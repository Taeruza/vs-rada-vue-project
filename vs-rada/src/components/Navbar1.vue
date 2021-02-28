<template>
  <nav class="navbar navbar-expand-md fixed-top navbar-dark">
    <b-link class="navbar-brand" to="/" >
      <img src="..\assets\logo.png" width="40" height="40" alt="Верхньосировотська сільська рада">
    </b-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse justify-content-center navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto text-center">
        <li class="nav-item active">
          <router-link class="nav-link" to="/" >Головна</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/news" >Новини</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/сommunity_card" >Картка громади</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/contacts" >Контакти</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/jobs" >Вакансії</router-link>
        </li>
      </ul>
      <span class="navbar-text">
        +38 (050) 877 6109
      </span>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
  .navbar {
    background: #304586;
    opacity: 96%;
  }

  .navbar-nav {
    font-size: 20px;
  }

  .navbar-nav {
    float:none;
    margin:0 auto;
    display: block;
    text-align: center;
  }

  .navbar-nav > li {
    display: inline-block;
    float:none;
  }

  .navbar-text {
    color: #ffffff;
  }
</style>