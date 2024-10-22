<template>
  <div id="app">
    <TheHeader v-if="showHeader" />
    <TimeBox />

    <div v-for="obj in todos" :key="obj.id" class="todos-item"> 
      {{ obj.title }}
      <img v-if="obj.url" :src="obj.url" :alt="obj.title">
    </div>

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
      todos: [
        {
          "userId": 1,
          "id": 1,
          "title": "titulo 1",
          "url": "https://via.placeholder.com/600/92c952",
          "completed": false

        },
        {
          "userId": 1,
          "id": 2,
          "title": "titulo 2",
          "url": "https://via.placeholder.com/600/771796",
          "completed": false
        },
        {
          "userId": 1,
          "id": 3,
          "title": "titulo 3",
          "url": "https://via.placeholder.com/600/24f355",
          "completed": false
        },
        {
          "userId": 1,
          "id": 4,
          "title": "titulo 4",
          "url": "https://via.placeholder.com/600/d32776",
          "completed": true
        },
        {
          "userId": 1,
          "id": 5,
          "title": "titulo 5",
          "url": "https://via.placeholder.com/600/56a8c2",
          "completed": false
        }
      ],
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

.todos-item {
  background-color: #2c3e50;
  color: aliceblue;
}
</style>
