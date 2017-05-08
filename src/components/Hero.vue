<template>
<section>
<img src="../assets/cover.jpg">
</section>
</template>

<script>
export default {
  name: 'hero',
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

h3 {
  font-weight: 900;
  font-size: 8rem;
  color: #FF902A;
  transform: rotate(-90deg);  
  
}

section {
    width: 100%;
}

section img {
  width: 100%;
  height: auto;
}

</style>
