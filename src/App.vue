<template>
  <div id="app">
    <DcHeader />
    <DcMainBlack />
    <DcMainBlue />
    <DcFooter />
  </div>
</template>

<script>
import DcHeader from './components/Header.vue';
import DcMainBlack from './components/MainBlack.vue';
import DcMainBlue from './components/MainBlue.vue';
import DcFooter from './components/FooterDc.vue';

export default {
  name: 'App',
  components: {
    DcHeader,
    DcMainBlack,
    DcMainBlue,
    DcFooter,
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
