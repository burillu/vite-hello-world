<template>
    <header>
        <h1>{{ text }}</h1>
    </header>
</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            text: 'La mia prima app con Vite!'
        }
    }
}
</script>

<style scoped>
h1 {
    color: blue;
}
</style>