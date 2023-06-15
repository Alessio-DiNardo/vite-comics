<script>
  import HeaderUpper from './components/HeaderUpper.vue';
  import HeaderUnder from './components/HeaderUnder.vue';
  import FooterUpper from './components/FooterUpper.vue';
  import FooterUnder from './components/FooterUnder.vue';
  
  export default {
    name: 'App',
    components: {
      HeaderUpper,
      HeaderUnder,
      FooterUpper,
      FooterUnder,

    }
  }
</script>

<template>
  <HeaderUpper/>
  <HeaderUnder/>
  <FooterUpper/>
  <FooterUnder/>
</template>

<style lang="scss">
  @import './styles/general.scss';

</style>
