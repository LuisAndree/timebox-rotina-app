<template>
  <div id="app">
    <TheHeader v-if="showHeader" />
    <TimeBox />

  </div>
</template>

<script>
import TimeBox from './components/TimeBox.vue'
import TheHeader from './components/TheHeader.vue'


export default {
  name: 'App',
  components: {
    TimeBox,
    TheHeader,
  },
  data() {
    return {
      showHeader: true,
    };
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
