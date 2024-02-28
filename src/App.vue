<script>
// importa il componente con:
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default{
  // inserisco il mio componente con components: 
  components: {
    AppTitle,
    AppHero,
  },
}


</script>

<template>
    <!-- titolo -->
    <AppTitle></AppTitle>
    <!-- jumbotron -->
    <AppHero></AppHero>
</template>

<style>

</style>