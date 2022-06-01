<template>
    <main class="main">
        <firtsSectionMain/>
        <secondSectionMain/>
        <thirdSectionMain/>
        <fourthSectionMain/>
    </main>
</template>

<script>
import firtsSectionMain from './firtsSectionMain.vue';
import secondSectionMain from './secondSectionMain.vue';
import thirdSectionMain from './thirdSectionMain.vue';
import fourthSectionMain from './fourthSectionMain.vue';
export default {
    name: 'AppMain',
    components: {
        firtsSectionMain,
        secondSectionMain,
        thirdSectionMain,
        fourthSectionMain,
    },
};
</script>

<style lang="scss" scoped>
</style>