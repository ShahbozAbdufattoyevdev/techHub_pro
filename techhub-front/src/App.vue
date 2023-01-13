<template>
<div class="container">
<Header />
 
</div>
</template>

<script>
import  Header from './components/HeaderSite.vue'
 
export default{
  name: 'App',
  components:{Header},
 
}
</script>



<style scoped>
*{
cursor: pointer;
}
body{
  background-color: yellow;
}
.container{
    width: 1290px;
    margin: auto;
    border: dotted 2px red;
}
</style>
