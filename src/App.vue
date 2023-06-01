<template>
  <div id="app">
    <h2>img comparison slider</h2>
    <img-comparison-slider>
      <img slot="first" src="./assets/3.jpg" width="510"/>
      <img slot="second" src="./assets/4.jpg" width="510"/>
    </img-comparison-slider>
  </div>
</template>

<script>
import 'img-comparison-slider';
export default {
  name: 'App',
}
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
