<template>
  <div id="app">
    <PageTitle msg="Basic Vue Blog"/>
    <Navigation/>
    <BlogFeed/>
  </div>
</template>

<script>
import PageTitle from './components/PageTitle.vue'
import Navigation from './components/Navigation.vue'
import BlogFeed from './components/BlogFeed.vue'

export default {
  name: 'app',
  components: {
    PageTitle,
    Navigation,
    BlogFeed
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #413C58;
  margin-top: 60px;
}
</style>
