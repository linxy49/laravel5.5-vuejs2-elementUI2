<template>
    <div>
        <h1>Hello, {{ msg }}!</h1>
        <router-link to="/hello">Hello</router-link>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    data() {
        return {
            msg: 'World'
        }
    }
}
</script>

<style>
</style>
