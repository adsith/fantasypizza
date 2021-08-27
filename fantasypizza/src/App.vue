<template>
  <div id="mainContainer">
    <Header />
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
  },
  data() {
    return{
      bodyStyle:{
        backgroundColor: "#58ABE5"
      }
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#mainContainer {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

body {
  margin: 0;
  padding: 0;
  background-color: #58ABE5;
}
</style>
