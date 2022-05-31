<template>
    <header class="header">
        <div class="left-header">
            <nav>
                <ul>
                    <li v-for="(item, index) in headerMenu" :key="index"> <h3> {{ item.text }}</h3></li>
                </ul>
            </nav>
        </div>
        <div class="center-header">
            <img class="logo" src="" alt="">
        </div>
        <div class="right-header">
            <ul>
                <li v-for="(item, index) in rightHeader" :key="index">
                <i :class="item.icon"></i></li>
            </ul>
        </div>

    </header>
</template>

<script>

export default {
    name: 'AppHeader',
    props: {
        headerMenu: Array,
        rightHeader: Array, 

    },
    components: {
    }
}
</script>

<style lang="scss" scoped>
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>