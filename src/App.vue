<template>
  <AppTitle />
</template>

<script>
import AppTitle from './components/AppTitle.vue';
export default {
  name: 'App',
  components: {

    AppTitle

  },
  data() {
    return {
      message: 'Hellooo World!'
    }
  }
}
</script>

<style lang="css" scoped></style>