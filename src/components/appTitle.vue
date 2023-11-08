<template>
    <div>
        <h1>{{ title }}</h1>
    </div>
</template>

<script>
export default {
    name: 'AppTitle',
    data () {
        return {
            title: 'La mia prima app con Vite!',
        }
    }
}
</script>

<style lang="css" scoped>
h1 {
    text-align: center;
    margin-top: 0;
    margin-bottom: 5px;
}
</style>