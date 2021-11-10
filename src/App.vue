<template>
  <div id="app">
    <Title msg="Text From App.vue"/>
  </div>
</template>

<script>
import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style>
  h1{
    display: inline
  }
  img{
    vertical-align: middle
  }
</style>
