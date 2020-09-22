<template>
  <div id="body-grid">
    
    <body-upper></body-upper>
    <body-middle></body-middle>
    <body-bottom></body-bottom>
     
    

  </div>
</template>

<script>
import BodyUpper from "./upper.vue";
import BodyMiddle from "./middle.vue"
import BodyBottom from "./bottom.vue";


export default {
  name: 'body-grid',
  components: {
    BodyUpper,
    BodyMiddle,
    BodyBottom,

  
  }
}
</script>

<style>
#body-grid {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
