<template>
  <div id="app">
    <Title/>
    <Carousel />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Carousel from './components/Carousel.vue'


export default {
  name: 'App',
  components: {
    Title,
    Carousel
    
  }
}
</script>

<style lang="scss">

</style>
