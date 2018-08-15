<template>
  <div id="app">
    <input-tag></input-tag>
  </div>
</template>

<script>
  import InputTag from '@/components/Input-tagging.vue';

  export default {
    name: 'app',
    data () {
      return {
        x: ''
      }
    },
    components:{ InputTag }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
