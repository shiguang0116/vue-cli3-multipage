<template>
    <div>
        <h1>首页</h1>
        <a href="shop.html">jump to shop.html</a>

        <div>
            <img alt="Vue logo" src="@/assets/logo.png">
            <HelloWorld msg="HelloWorld组件"/>
        </div>
    </div>
</template>

<script>
    import HelloWorld from '@/components/HelloWorld.vue'

    export default {
        name: "index",
        components: {
            HelloWorld
        }
    }
</script>

<style scoped>

</style>