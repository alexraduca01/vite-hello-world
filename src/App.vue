<template>
  <div class="main-container">
    <AppTitle/>
    <AppHero/>
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: { 
    AppTitle,
    AppHero,
  },
  data () {
    return {

    }
  }
}
</script>

<style lang="css" scoped>
.main-container {
  color: dodgerblue;
}
</style>