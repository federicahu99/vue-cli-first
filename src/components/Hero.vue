<template>
 <div id="jumbo-container"> 
  <p>
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, in earum. Laboriosam suscipit voluptatibus velit reiciendis, qui minus officiis possimus sed et hic assumenda natus consequuntur voluptates voluptatum incidunt tempora!
  </p>
  <img src="../assets/logo.png" alt="">
 </div>
</template>

<script>
export default {
  name: 'JumboComponent',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#jumbo-container {
    height : 30vh;
    background-color:azure;
    display: flex;
    padding: 30px;
}

p{
  font-size: 25px;
}
</style>
