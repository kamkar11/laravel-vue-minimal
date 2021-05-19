<template>
    <div class="app">
        <Navbar></Navbar>
        <router-view></router-view>
    </div>
</template>

<script>
    import './Styles/app.scss'
    export default {
        name: "App",
        comments: {
            Navbar: () => import('./Components/Navbar.vue')
        }
    }
</script>

<style scoped>

</style>
