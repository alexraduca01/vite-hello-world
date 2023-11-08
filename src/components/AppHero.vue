<template>
  <header>
    <div>
      <img src="../../public/img/dawg.png" alt="dawg">
    </div>
    <h2>Jumbotron</h2>
  </header>
</template>

<script>
  export default {
    name: 'AppHero',
    data(){
      return {
        
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