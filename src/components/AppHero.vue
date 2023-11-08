<template>
  <header>
    <div>
      <img :src="path" alt="dawg">
    </div>
    <h2>Jumbotron</h2>
  </header>
</template>

<script>
  export default {
    name: 'AppHero',
    data(){
      return {
        path: '../../public/img/dawg.png',
      }
    }  
  }
</script>

<style lang="css" scoped>
header > div {
  display: flex;
  justify-content: center;
  margin-bottom: 5px;
}
h2 {
  text-align: center;
  margin-bottom: 5px;
}
</style>