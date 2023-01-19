<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <h1> {{ title }} </h1>
</template>

<style scoped>
h1 {
    text-align: center;
    color: coral;
    margin-top: 4rem;
    font-size: 50px;
}
</style>