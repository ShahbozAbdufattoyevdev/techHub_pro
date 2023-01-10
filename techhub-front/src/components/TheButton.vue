<template>
    <div>
        <h2
            :class="count === 0 ? 'color: red' : ''"
        >
            {{ count }}
        </h2>
        <button @click="inc">+</button>
        <button
            :disabled="count === 0"
            @click="dec"
        >-
        </button>
    </div>
</template>

<script>
export default {
    name: "TheButton",
    data() {
        return {
            count: 0
        }
    },
    methods: {
        inc() {
            this.count++
        },
        dec() {
            this.count--
        }
    }
}
</script>

<style scoped>
button {
    color: blue;
}

</style>