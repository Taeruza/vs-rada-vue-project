<template>
  <nav class="navbar navbar-expand-md fixed-top navbar-dark">
    <a class="navbar-brand" href="#">
      <img src="..\assets\logo.png" width="50" height="50" alt="Верхньосировотська сільська рада">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse justify-content-center navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto text-center">
        <li class="nav-item active">
          <a class="nav-link" href="#">Головна<span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Новини</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Картка громади</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Контакти</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Вакансії</a>
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