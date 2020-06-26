<template>
    <div>
        <div>
            底部导航
            <a href="javascript:;" :class="{on: '/msite' === $route.path}" @click="goto('/msite')">msite</a>
            <a href="javascript:;" :class="{on: '/search' === $route.path}" @click="goto('/search')">search</a>
            <a href="javascript:;" :class="{on: '/order' === $route.path}" @click="goto('/order')">order</a>
            <a href="javascript:;" :class="{on: '/profile' === $route.path}" @click="goto('/profile')">profile</a>
        </div>
    </div>
</template>
<script>
export default {
    methods: {
        goto(path) {
            this.$router.replace(path)
        }
    }
}
</script>
<style scoped>
    .on {
        color: red;
    }
</style>