<template>
  <div id="app">
    <DcHeader />
    <DcMainBlack />
    <DcMainBlue />
    <DcFooter />
    <FooterIcons />
  </div>
</template>

<script>
import DcHeader from './components/Header.vue';
import DcMainBlack from './components/MainBlack.vue';
import DcMainBlue from './components/MainBlue.vue';
import DcFooter from './components/FooterDc.vue';
import FooterIcons from './components/FooterIcons.vue';

export default {
  name: 'App',
  components: {
    DcHeader,
    DcMainBlack,
    DcMainBlue,
    DcFooter,
    FooterIcons,
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
