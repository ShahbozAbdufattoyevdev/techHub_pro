<template>
 
<HeaderSite />
 <MainApp />
<TheFooter />
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainApp from './components/MainApp.vue'
import TheFooter from './components/TheFooter.vue'
export default{
  name: 'App',
  components:{HeaderSite, MainApp, TheFooter},
}
</script>



<style scoped>
*{
cursor: pointer;
list-style: none;
}

.container{
    width: 1290px;
    margin: auto;
    border: dotted 2px red;
}
</style>
