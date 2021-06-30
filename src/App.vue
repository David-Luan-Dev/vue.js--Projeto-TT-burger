<template>
  <div id="app">
   
    <Header />
    <img src="./img/logo_TT_transp.png" alt="" id="logo-tt">
    <h1>Acompamento de Vendas</h1>
    <div class="acompamento">
      <ul>
        <li>primeiro item</li>
        <li>segundo item</li>
        <li>terceiro item</li>
      </ul>
    </div>

  </div>
</template>

<script>
import './assets/styles/globa.css';

import Header from './components/Header';

import './fonts/Brothers Regular.otf'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>
<style>

#logo-tt{
    width: 250px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    
}
h1{
  font-family: Brothers;
  text-align: center;
 
}
ul {
  color: aliceblue;
  display: inline;
   text-align: center;
   display: grid;
   grid-template-columns: auto;
  
}
div .acompamento{
background-color: black;
}


</style>