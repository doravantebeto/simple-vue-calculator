<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator></Calculator>
  </div>
</template>

<script>
import Calculator from "./main/Calculator";
export default { components: { Calculator } };
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

body {
  margin: 0px;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #ffffff;
  background: linear-gradient(to right, #fe346e, #2c003e);
}
</style>