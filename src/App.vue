<template>
  <div id="app">
   <DesafioUno></DesafioUno>
  </div>

  
</template>

<script>
import DesafioUno from './components/DesafioUno.vue';
export default {
  name: "App",
  components: {DesafioUno},
  data() {
    return {
    };
  },
};
</script>

<style lang="scss">
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
