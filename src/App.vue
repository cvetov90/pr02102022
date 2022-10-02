<template>
  <NoteComp></NoteComp>
</template>

<script>
import NoteComp from './components/NoteComp.vue';

export default {
  name: 'App',
  components: {
    NoteComp
}
}
</script>

<style>
#app {
  margin: 0;
  padding: 0;
  left: 0;
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
