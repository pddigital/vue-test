<template>
<div>
  <navigation></navigation>
  <hero></hero>
  <titlebar></titlebar>
  <jose></jose>
</div>
</template>

<script>
import Navigation from './Navigation'
import Hero from './Hero'
import Titlebar from './Titlebar'
import Jose from './Jose'

export default {
  name: 'homepage',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Hero,
    Titlebar,
    Navigation,
    Jose
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
