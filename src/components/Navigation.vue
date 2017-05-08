<template>
  <nav>


  
  </nav>
</template>

<script>
export default {
  name: 'navigation',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: 900;
  font-size: 5rem;
  color: #FF902A;
  text-align: right;
  line-height: 1;
}

h2 {
  font-weight: 900;
  font-size: 3rem;
  color: #FF902A;
  text-align: right;
  line-height: 1;
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

nav {
  display: none;
  position: fixed;
  top: 0;
  width: 100%;
  height: 100px;
  padding: 1%;
  background-color: #FF902A;
  color: #FF902A;
}



</style>
