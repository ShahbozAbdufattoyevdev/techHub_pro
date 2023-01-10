<template>
    <div>
        <the-navbar />
        <TheMain />
    </div>
</template>

<script>

import TheNavbar from "@/components/TheNavbar";
import TheMain from "@/components/TheMain";
export default {
  name: 'App',
  components: {
      TheNavbar,
      TheMain
  }
}
</script>

<style>

</style>
