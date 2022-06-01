<template>
    <header class="header">
        <div class="left-header">
                <ul>
                    <li v-for="(item, index) in headerMenu" :key="index"> <h4> {{ item.text }}</h4><i class="fas fa-angle-down"></i></li>
                </ul>
        </div>
        <div class="center-header">
            <img class="logo" src="../assets/img/dark-logo.png" alt="">
        </div>
        <div class="right-header">
            <ul>
                <li v-for="(item, index) in rightHeader" :key="index">
                <i :class="item.icon"></i></li>
            </ul>
            <span><input type="text" placeholder="Search"><i class="fas fa-search"></i></span>
            
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

    .header{
        height: 100px;
        width: 90%;
        margin: 0 auto;
        display: flex;
        align-items: center;
    }
    .left-header{
            width: 50%;
        }
    .center-header, .right-header{
        width: 25%;
    }
    .center-header img {
        width: 50%;
    }
    ul{
        display: flex;
        list-style: none;
    }
    li{
        margin-right: 10px;
        display: flex;
        align-items: center;
        opacity: 0.7;
    }
    .left-header i{
        font-size: 0.7em;
        margin-top: 4px;
        margin-left: 2px;
    }

    .right-header{
        display: flex;
        align-items: center;
    }
   
</style>