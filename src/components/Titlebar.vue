<template>
<div class="row title">

<div class="col-md-10">
  <h1 class="slideLeftReturn">WE ARE CHEFS</h1>
  <h2 class="slideLeftReturn">2016 ANNUAL REPORT</h2>
</div>
<div class="col-md-2">
<img class="vanishIn logoImg" src="../assets/wcklogo.png">
</div>

</div>
</template>

<script>
export default {
  name: 'titlebar',
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
  margin: 0;
}

h2 {
  font-weight: 900;
  font-size: 3rem;
  color: #FF902A;
  text-align: right;
  line-height: 1;
  margin: 0;
}

.logoImg {
  width: 115px;
}

.title {
  margin: 2%;
}

.vanishIn {
  -webkit-animation-duration: 3s;
  -moz-animation-duration: 3s;
  -o-animation-duration: 3s;
  animation-duration: 3s;
  -webkit-animation-name: vanishIn;
  animation-name: vanishIn;
}

@keyframes vanishIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}


.slideLeftReturn {
  -webkit-animation-duration: 1.5s;
  -moz-animation-duration: 1.5s;
  -o-animation-duration: 1.5s;
  animation-duration: 1.5s;
  -webkit-animation-name: slideLeftReturn;
  animation-name: slideLeftReturn;
}

@keyframes slideLeftReturn {
  0% {
    opacity: 0;
    transform-origin: 0 0;
    transform: translateX(-100%);
  }

  100% {
    opacity: 100%;
    transform-origin: 0 0;
    transform: translateX(0%);
  }
}

</style>
