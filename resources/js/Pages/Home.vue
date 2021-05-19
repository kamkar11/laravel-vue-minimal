<template>
    <div>
        <h1>bla sdgosgosih</h1>
<!--        <h1>-->
<!--            {{ count }}-->
<!--        </h1>-->
<!--        <button class="btn" @click="$store.commit('increament')">INCREAMENT</button>-->
    </div>
</template>

<script>
    import { mapState } from 'vuex';

    export default {
        name: "home",
        computed: {
            ...mapState({
                count: state => state.count()
            }),
        }
    }
</script>

<style scoped>

</style>
