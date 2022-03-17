<!-- https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Vue_getting_started -->

<template>
<div id="app"> 
  <h1>Contoso Pizzas</h1>
  <div> <pizzas-item> </pizzas-item></div>
  <img alt="Vue logo" src="./assets/logo.png">
  
</div>
</template>

<script>
import PizzasItem from './components/PizzasItem.vue';

export default {
  name: 'App',
  components: {
    PizzasItem
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
