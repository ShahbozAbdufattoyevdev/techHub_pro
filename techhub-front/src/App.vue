<template>
 
<Header />
 <MainApp />
 
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

.container{
    width: 1290px;
    margin: auto;
    border: dotted 2px red;
}
</style>
