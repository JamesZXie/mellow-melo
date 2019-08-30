<template>
    <h1 @click="increment">{{ counter }}</h1>
</template>

<script>

export default {
    data() {
        return {
            hello: "hello",
        }
    },
    computed: {
        counter() {
            return this.$store.state.counter;
        }
    },
    methods: {
        increment() {
            this.$store.state.counter++;
        }
    }
}

</script>