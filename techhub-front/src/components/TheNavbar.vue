<template>
    <div>
        <the-link />
        <h1>Hello</h1>
    </div>
</template>

<script>
import TheLink from "@/components/TheLink";
export default {
    name: "TheNavbar",
    components: {TheLink}
}
</script>

<style scoped>
h1 {
    color: red;
}
</style>