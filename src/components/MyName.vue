<template>
    <div>
        <h2>{{ name }}</h2>
    </div>
</template>

<script>
export default {
    name: 'MyName',
    props: {
        name: String
    }
}
</script>

<style lang="css" scoped>
    h2{
        color:rgb(76, 0, 255)
    }
</style>