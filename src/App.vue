<template>
  <div id="root">
    <div id="bg">
      <MyTitle></MyTitle>  <!-- scritto anche <MyTitle />  -->
      <MyJumbo></MyJumbo>
    </div>
  </div>
</template>

<script>
import TitleComponent from './components/Title.vue'
import JumboComponent from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    MyTitle: TitleComponent, // creo nome del tag che voglio : nome-componente ,
    MyJumbo: JumboComponent,
  }
}
</script>

<style> /*  */
* {
  padding: 0;
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
#bg{
  background-color: lightgrey;
  height: 100vh;
  width: 100vw;

}
</style>
