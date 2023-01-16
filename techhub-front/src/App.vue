<template>

  <HeaderSite />
  <MainApp />
  <TheFooter />
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainApp from './components/MainApp.vue'
import TheFooter from './components/TheFooter.vue'
export default {
  name: 'App',
  components: { HeaderSite, MainApp, TheFooter },
}
</script>



<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  text-decoration: none;
  list-style: none;
}

.container {
  padding: 0px 12px;
  margin: 0 auto;
  max-width: 1200px;
}
</style>
