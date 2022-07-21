<template>
 <div id="jumbo-bg"></div>
</template>

<script>
export default {
  name: 'JumboComponent',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#jumbo-bg {
    height : 30vh;
    background-image: url('../assets/logo.png');
    background-repeat: repeat-x;
    background-size: contain;
}
</style>
