<template>
  <div id="content">
    <img src="../../assets/logo.png">
    <h1>{{ msg }}</h1>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'content',
    data () {
      return{
        msg: "Título Teste"
      }
    }
  }
</script>

<style>
  #content {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
