<template>
    <div>
        <h1>Hello, Laravel 5.5.* + Vuejs2.* + ElementUI2.*</h1>
        <el-button @click="visible = true">Button</el-button>
        <el-dialog :visible.sync="visible">
            <p>Message</p>
        </el-dialog>
    </div>
</template>

<script>
export default {
    data() {
        return {
            visible: false
        }
    }
}
</script>

<style>
</style>
