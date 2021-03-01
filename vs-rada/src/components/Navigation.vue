<template>
    <div class="navigation">
      <div>
        <!-- Using modifiers -->
        <b-navbar-item v-b-toggle.contr-toggle> Управління
          <b-icon icon="chevron-down" aria-hidden="true"></b-icon>
        </b-navbar-item>
        
        <!-- Element to collapse -->
        <b-collapse id="contr-toggle">
          <b-navbar-item v-b-toggle.structure-toggle> Структура сільської ради
            <b-icon icon="chevron-down" aria-hidden="true"></b-icon>
          </b-navbar-item><br>
          <!--<b-link to="/">Структурні підрозділи виконавчих органів</b-link> -->
        </b-collapse>

        <b-collapse id="structure-toggle">
          <b-link to="/">Керівництво</b-link> <br>
          <b-navbar-item v-b-toggle.apparat-toggle> Апарат
            <b-icon icon="chevron-down" aria-hidden="true"></b-icon>
          </b-navbar-item><br>
        </b-collapse>

        <b-collapse id="apparat-toggle">
          <b-link to="/">Відділ організаційно-правового забезпечення та управління персоналом</b-link> <br>
          <b-link to="/">Відділ земельних відносин, комунальної власності та житлово-комунального господарства</b-link> <br>
          <b-link to="/">Відділ соціального захисту населення</b-link> <br>
          <b-link to="/">Відділ фінансового і господарського забезпечення</b-link> <br>
        </b-collapse>

      </div>
    </div>
</template>

<script>
export default {
    name: 'Navigation'
}
</script>

<style scoped>  
.navigation {
  background: #ffffff;
  box-shadow: 0px 2px 10px 0px #a4a4a454;
  margin-top: 50px;
  margin-left: 50px;
  text-align: left;
  padding: 20px;
  font-size: 20px;
}

#contr-toggle {
  padding-left: 20px;
}

#structure-toggle {
  padding-left: 40px;
}

#apparat-toggle {
  padding-left: 60px;
}
</style>