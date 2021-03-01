<template>
  <div class="navbar-main">
    <b-navbar toggleable="lg" type="dark" shadow="lg" style="z-index: 100;">
      <b-navbar-brand to="/">
          <img src="..\assets\logo.png" width="40" height="40" alt="Верхньосировотська сільська рада">
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/" >Головна</b-nav-item>
          <b-nav-item to="/news">Новини</b-nav-item>

          <b-nav-item-dropdown to="/сommunity_card" text="Картка громади" left>
            <b-dropdown-item to='/vs'>c. Верхня Cировотка</b-dropdown-item>
            <b-dropdown-item to='/vb'>c. Великий Бобрик</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>

          <b-nav-item to="/contacts">Контакти</b-nav-item>
          <b-nav-item to="/jobs">Вакансії</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="tel:0542690004" active>+38 (0542) 690-004</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div> 
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>
.navbar-main {
  box-shadow: 0px 2px 10px 0px #A4A4A4;
}
.navbar {
  background: #304586;
  opacity: 96%;
}

.navbar-nav {
  font-size: 20px;
}

.navbar-item {
  color: #ffffff;
}

.dropdown:hover > .dropdown-menu {
  display: block;
}

.dropdown > .dropdown-toggle:active {
  pointer-events: none;
}
.dropdown-menu {
  margin-top: 0;
}
</style>