<template>
  <div class="home">
    <h1>DAWN'S SWEET TREATS</h1>
<!-- //Make an unordered list of all the cakes  -->
<ol>
  <li>Cakes</li>
  <li>Cupcakes</li>
  <li>Macarons</li>
</ol>
    
   <!-- <h1>This is the home page</h1> -->
   <!-- <img src="../assets/Cakes/cupcakewallpaper2.avif"  alt="cake" id="cover-pic" /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
 #cover-pic {
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.5;
  background-size: cover; 
  background-position: center;
  /* background: "url(../assets/Cakes/cupcakewallpaper.avif)"; */
  background-size: cover;
  object-fit: cover;
} 

</style>
