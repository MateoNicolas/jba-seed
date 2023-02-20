<template>
  <div id="app">root</div>
  <Menus/>
</template>

<script>
import Menus from './components/menus.vue';

export default {
  name: 'App',
  components:{
    Menus,
  }
   
};
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
</style>
