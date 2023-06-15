<script>
  import AppHeader from './components/AppHeader.vue';
  import FooterUpper from './components/FooterUpper.vue'
  import FooterUnder from './components/FooterUnder.vue';
  export default {
    name: 'App',
    components: {
      AppHeader,
      FooterUpper,
      FooterUnder

    }
  }
</script>

<template>
  <AppHeader/>
  <FooterUpper/>
  <FooterUnder/>
</template>

<style lang="scss">
  @import './styles/general.scss';

</style>
