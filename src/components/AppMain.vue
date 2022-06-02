<template>
    <main class="main">
        <firtsSectionMain/>
        <secondSectionMain :cards="cardCourses"/>
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
    data: function () {
        return {
            cardCourses: [
                {
                    image:"course-01.jpg",
                    price:"40.00",
                    course: "Learning to Write as a Professional Author",
                    lessons:"20",
                    students:"50",
                },
                {
                    image:"course-02.jpg",
                    price:"0.00",
                    course:"Customer-centric Info-Tech Strategies",
                    lessons:"24",
                    students:"759",

                },
                {
                    image:"course-03.jpg",
                    price:"19.00",
                    course:"Open Programming Courses for Everyone: Phyton",
                    lessons:"17",
                    students:"62",
                },
            ],
        };
    },
};
</script>

<style lang="scss" scoped>
</style>