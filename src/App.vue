<template>
  <div id="root">
    <MyTitle ></MyTitle>
    <MyJumbo></MyJumbo>
  </div>
</template>

<script>
import TitleComponent from './components/Title.vue'
import JumboComponent from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    MyTitle: TitleComponent,
    MyJumbo: JumboComponent,
  }
}
</script>

<style>

</style>
