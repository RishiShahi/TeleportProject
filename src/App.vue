<template>
    <h1>This is the app Component</h1>
    <Detail />
     <Show >
        {{message}}
      </Show>
</template>

<script>
import Detail from './components/Detail.vue'
import Show from './components/Show.vue'

export default {
   components : { Detail, Show },
   data() {
     return {
       message: 'Message form parent',
     }
   }
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
