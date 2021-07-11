<template>
    <div class="firstView">
        <myHeader />
        <offer />
    </div>
</template>

<script>
    import myHeader from './myHeader.vue'
    import offer from './offer.vue'
    export default {
        name: 'firstView',
        components: {
            myHeader,
            offer
        }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/styles/variables.scss";
    .firstView{
        background-color: $darkBlueBgColor;
        min-height: 100vh;
    }

</style>
