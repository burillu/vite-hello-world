<template>
  <AppTitle />
  <AppHero />
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero
  },
  data() {
    return {
      message: 'Hellooo World!'
    }
  }
}
</script>

<style lang="css" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>