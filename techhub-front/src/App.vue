<template>
<div class="container">
<Header />
</div>
</template>

<script>
import  Header from './components/HeaderSite.vue'
export default{
  name: 'App',
  components:{Header}
}
</script>

<style scoped>
*{
cursor: pointer;
}
body{
  background-color: yellow;
}
</style>
