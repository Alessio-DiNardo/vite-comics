<script>
  import HeaderUpper from './components/HeaderUpper.vue';
  import AppJumbo from './components/AppJumbo.vue';
  import HeaderUnder from './components/HeaderUnder.vue';
  import AppMain from './components/AppMain.vue';
  import FooterUpper from './components/FooterUpper.vue';
  import FooterUnder from './components/FooterUnder.vue';
  
  export default {
    name: 'App',
    components: {
      HeaderUpper,
      AppJumbo,
      HeaderUnder,
      AppMain,
      FooterUpper,
      FooterUnder,

    }
  }
</script>

<template>
  <HeaderUpper/>
  <AppJumbo/>
  <HeaderUnder/>
  <AppMain/>
  <FooterUpper/>
  <FooterUnder/>
</template>

<style lang="scss">
  @import './styles/general.scss';

</style>
