<template>
  <div class="homePage">
    <input class="btn" type="button" value="Démarrer">
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  layout: 'defaultLayout'
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&family=Poppins:wght@100;200;400;600;700;800;900&display=swap');

body{
  font-family: 'Poppins', sans-serif;
}

.homePage{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  
  .btn{

  }
}
</style>
