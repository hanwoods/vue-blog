<template>
  <v-container> 
    <v-layout row wrap name-text>
      <v-flex xs12>
        <vue-typer text='Hannah Woods' preTypeDelay="1000" :repeat="0"></vue-typer>
      </v-flex>
    </v-layout>
    <v-layout row wrap tag-line>
      <v-flex xs12>
        <vue-typer text='Software Developer, Vancouver BC.' preTypeDelay="3000" :repeat="0"></vue-typer>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import { VueTyper } from 'vue-typer'

export default {
  name: 'PageTitle',
  components: {
    VueTyper
  }
}
</script>

<style>
.name-text {
  font-size: 70px;
  font-weight: bold;
  padding-top: 300px;
}

.tag-line {
  font-size: 30px;
}
</style>

