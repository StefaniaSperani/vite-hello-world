<template>
  <AppHero />
  <AppTitle />

</template>


<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero
  },
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>


<style lang="css">
body {
  background-color: grey;
}
</style>