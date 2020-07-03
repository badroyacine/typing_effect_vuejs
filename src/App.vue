<template>
  <div id="app">
    <div class="overlay"></div>
    <TypeEffect />
  </div>
</template>

<script>
import TypeEffect from './components/TypeEffect.vue'

export default {
  name: 'App',
  components: {
    TypeEffect
  }
}
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Pangolin&display=swap');

  body {
    margin: 0;
    padding: 0;
  }

  #app {
    // font-family: 'Righteous', arial;
    font-family: 'Pangolin', cursive, sans-serif;
    font-weight: 400;
    font-size: 4rem;
    color: #fff;
    background-image: url('assets/background-image.jpg');
    background-size: cover;
    width: 100%;
    min-height: 100vh;
    position: relative;
  }

  .overlay {
    background-color: rgba($color: #000000, $alpha: 0.5);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>
