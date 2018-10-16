<template>
  <div id="app">
    <v-app>
      <v-container>
        <PageTitle/>
        <Navigation/>
      </v-container>
    </v-app>
  </div>
</template>

<script>
import PageTitle from './components/PageTitle.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'app',
  components: {
    PageTitle,
    Navigation
  }
}
</script>

<style>
#app {
  font-family: 'Courier New', Courier, monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #47484C;
}
</style>
