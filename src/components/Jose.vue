<template>
  <div class="container">

  <div class="row">
  <div class="col-md-2">
  <h1>JOSÉ ANDRÉS</h1>
  </div>

  <div class="col-md-10 left-column">

  <div class="row">

    <img src="../assets/jose.jpg" id="josepic">
    <h2>At World Central Kitchen, <br>
      We Are Chefs.</h2>

    <div class="col-md-6 left-column">
      <p>We have a simple mission: to make sure that food is an agent of change around the world.</p>
        
      <p>Since we’ve started, our Chef Network has affected lives in Brazil, Cambodia, Cuba, Dominican Republic, Haiti, Nicaragua, Zambia and even here in the United States. Our chefs are passionate and our network is growing!</p>
        
      <p>In 2016, our Chef Network was able to act fast when Hurricane Matthew hit. We cooked thousands of meals for our friends in Cayes, Haiti. But we aren’t stopping there. In this report, you will see the impact that our Chef Network has made around the world.</p>
    </div>
    
    <div class="col-md-6">
       <p>World Central Kitchen is a catalyst of change through chef-driven programs that focus on improving health, education and employment. Using our chef-expertise, we will continue to invest in safe cooking methods, healthy school meals, and culinary training – empowering communities and strengthening economies around the world.</p>
  
       <p>I am so grateful to our friends who have joined the mission of World Central Kitchen. With your support, we will continue to grow each year, and our smart solutions will continue to inspire communities around the world.</p>

       <img src="../assets/josesignature.png" id="josesig">

    </div>
  

  </div>

  </div>
  </div>

  </div>

</template>

<script>
export default {
  name: 'jose',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  created: () => {
    function isInViewport(element) {
      var rect = element.getBoundingClientRect()
      var html = document.documentElement
      return (
        rect.top >= 0 &&
        rect.left >= 0 &&
        rect.bottom <= (window.innerHeight || html.clientHeight) &&
        rect.right <= (window.innerWidth || html.clientWidth)
      )
    }

    if(isInViewport(document.getElementById('josesig'))){
        console.log ('it hit')
    }

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  p {
    font-size: 1rem;
  }

  h1 {
    position: fixed;
    font-weight: 900;
    color: #D7554B;
    font-size: 6rem;
    -webkit-transform: rotate(-90deg);
    -moz-transform: rotate(-90deg);
    -ms-transform: rotate(-90deg);
    -o-transform: rotate(-90deg);
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
    white-space: nowrap;
    top: 300px;
    left: -250px;

  }
  
  h2 {
    font-weight: 900;
    color: #D7554B;
    font-size: 2.5rem;
    margin-bottom: 5%;
  }

 #josepic {
   width: 100%;
   height: 100%;
   margin-bottom: 2%;
 }

 #josesig {
   width: 75%;
 }

 .left-column {
   margin-left: 0;
   padding-left: 0;
 }

</style>
