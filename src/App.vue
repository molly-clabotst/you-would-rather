<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    Would you rather...
    <Options0></Options0>
    Would you rather...
    <Options1></Options1>
    Would you rather...
    <Options2></Options2>
    <Choices></Choices>
  </div>
</template>

<script>
  import Options2 from "./Options2";
  import Options1 from "./Options1";
  import Options0 from "./Options0";
import Choices from "./components/Choices";

export default {
  name: 'app',
  components: {
    Choices,
    Options0,
    Options1,
    Options2
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
