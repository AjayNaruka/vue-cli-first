<template>
  <div class="carousel-container">
    <i class="fas fa-arrow-left"></i>
    <div class="slide"></div>
    <i class="fas fa-arrow-right"></i>
  </div>
</template>

<script>
export default {

}
</script>

<style>

  .carousel-container{
  height: 500px;
  width: 100%;
  background-color: red;
  display: flex;
  align-items: center;
  justify-content: center;
  }
  .slide{
    width: 60%;
    height: 90%;
    background-color: blue;
  }
  i{
    margin:0 10px
  }

</style>