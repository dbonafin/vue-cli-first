<template>
  <div id="app">
    <MyTitle msg="La mia prima app con Vue CLI"/>
    <MyJumbo></MyJumbo>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue';
import MyJumbo from './components/MyJumbo.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
