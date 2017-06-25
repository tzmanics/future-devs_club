<template>
  <div id="app">
    <header>
      <img src="./assets/fdc-logo_01.png" alt="Future Devs Club logo" id="header-logo">
    </header>
    <main>
      <intro></intro>
    </main>
  </div>
</template>

<script>
import Intro from './components/Intro'

export default {
  name: 'app',
  components: {
    Intro
  }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

main {
  width: 80%;
  margin: 10px auto;
  padding: 5px;
  border: solid 3px yellow;
  text-align: center;
}

header {
  margin: 0;
  height: 50px;
  padding: 9px 0 0 5px;
  background-color: aqua;
}

#header-logo {
  width: 40px;
  float: left;
}

</style>
