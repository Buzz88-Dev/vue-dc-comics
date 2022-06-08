<template>
  <div id="app">
    <DcHeader />
    <DcMain />
  </div>
</template>

<script>
import DcHeader from './components/Header.vue';
import DcMain from './components/Main.vue';

export default {
  name: 'App',
  components: {
    DcHeader,
    DcMain,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 100%;
}
</style>
