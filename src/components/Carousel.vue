<template>
  <div class="jumbotron">
    <div class="square">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam fugiat quas blanditiis eos nemo tempore atque, neque similique, modi voluptate consectetur debitis officia unde non nulla enim, nobis ullam. Iste.
    </div>
    <div class="square">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nobis temporibus veritatis repudiandae deserunt nesciunt eius earum voluptas excepturi molestiae quae dolor, quasi dolores quibusdam, est voluptates, eos aut nulla eligendi!</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

  .jumbotron{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 300px;
    width:100%;
    background-color:red;
    background-image: url('../assets/mountain.jpg');
    background-size: cover;
  }
  .square{
    width: 50%;
    padding: 20px;
    background-color: blue;
    margin: 0 25px;
  }

</style>