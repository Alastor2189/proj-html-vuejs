<template>
  <div class="jumbotron">
      <div class="title-jumbo">
          <h2> Commence Business</h2>
          <h1> Distant Mentoring Program</h1>
          <button> Download Free guidebook <i class="fas fa-long-arrow-alt-right"></i></button>
      </div>

  </div>
</template>

<script>
export default {
    name:'firstSectionMain',
}
</script>

<style lang="scss" scoped>
    .jumbotron {
        background-image: url(../assets/img/home-3-hero-bg.jpg);
        width: 100%;
        height: 75vh;
        background-size: cover;
        position: relative;
    }
    .title-jumbo {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100%;
        color: white;

        h2 {
            font-size: 2em;
        }
        h1 {
            font-size: 3em;
        }

        button {
            color: #20ad96;
            height: 40px;
            width: 300px;
            font-weight: bold
        }
 };
 
</style>