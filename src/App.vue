<template>
  <div id="app">
    <AppHeader :headerMenu="headerMenu" :rightHeader="rightHeader" />
    <AppMain />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  data: function () {
    return {
      headerMenu : [{
        text: "Home"
      },
      {
        text: "Pages"
      },
      {
        text: "Courses"
      },
      {
        text: "Features"
      },
      {
        text: "Blog"
      },
      {
        text: "Shop"
      },
      ],

      rightHeader :[
        {
          icon: "fas fa-shopping-cart"
        }
      ]
    };
  },
};
</script>

<style lang="scss" scoped>

</style>
