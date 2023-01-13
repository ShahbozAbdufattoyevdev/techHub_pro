<template>
<div class="container">
<Header />
 <MainApp />
</div>
</template>

<script>
import  Header from './components/HeaderSite.vue'
import MainApp from './components/MainApp.vue'
export default{
  name: 'App',
  components:{Header, MainApp},
 
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
