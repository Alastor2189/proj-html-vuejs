<template>
  <div class="container">
      <div class="work-culture">
          <h4> everything in maxcoach</h4>
            <h2> Learn about our Work Culture at MaxCoach</h2>
            <p> Spend some time to visit our website or head office and discover our current courses, enrollment procedure, and registration deadline. We're opening new classes every beginning of each month.</p>
            <p class="guide"> Have questions? <button>Get free guide <i class="fas fa-long-arrow-alt-right"></i></button></p>
      </div>
      <div class="work-image">
          <img class="circle-2" src="../assets/img/maxcoach-shape-02.png" alt="">
          <img class="cross" src="../assets/img/maxcoach-shape-07.png" alt="">
          <div class="cross-2">
                <img  src="../assets/img/maxcoach-shape-07.png" alt="">
          </div>
          <img class="girl" src="../assets/img/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="">
          <img class="work" src="../assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="">
      </div>
      <div class="stats">
        <div class="learners">
            <h2>129+</h2>
            <h3>enrolled learners</h3>
        </div>
        <div class="session">
            <h2>80</h2>
            <h3>finished sessions</h3>
        </div>
        <div class="rate">
            <h2>4%</h2>
            <h3>satisfaction rate</h3>
        </div>
      </div>
      <div class="image-upgrade">
          <img class="upgrade" src="../assets/img/stock-full-hd-11-670x450.jpg" alt="">
          <img class="youtube" src="../assets/img/icon-youtube-play.png" alt="">
          <img class="cross-3" src="../assets/img/maxcoach-shape-07.png" alt="">
          <img class="shape-5" src="../assets/img/maxcoach-shape-05.png" alt="">
      </div>
      <div class="upgrade-text">
          <h4>how we work</h4>
          <h2>Upgrade Your Skills Upgrade Your Life</h2>
          <p>Opening up more opportunities in front of you to get the ticket to more enjoyable dor in life. Getting equipped with new skills for new sets of insights into your career.</p>
          <button> Download free guidebook</button>
      </div>
  </div>
  
</template>

<script>
export default {
    name:'secondSectionMain',
}
</script>

<style lang="scss" scoped>
    .container {
    width: 85%;
    margin: 200px auto 0 ;
    display: flex;
    flex-wrap: wrap;

    .work-culture{
        width: 30%;
        
    }
    .work-image {
        width: 70%;
        position: relative;

        .work {
            width: 62%;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 10;

        }
        .circle-2 {
            position: absolute;
            bottom: -50%;
            right: 30%;
            z-index: 100;
        }
        .girl {
            position: absolute;
            z-index: 100;
            top: -50%;
            right: 10%;
        }
        .cross{
            position: absolute;
            top: -45%;
            right: 20%;
        }
        .cross-2 {
            position: absolute;
            top: -28%;
            right: 19%;
            z-index: 2;
            background-color: white;
            width: 169px;
            padding: 5px;
        }
    }
    .stats{
        width: 60%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        margin-top: 150px;
        margin-bottom: 200px;

        .learners, .session, .rate{
            display: flex;
            align-items: center;
            flex-direction: column;
        }
        h2 {
            color: #20ad96;
            font-size: 2em;
            margin-bottom: 0;
        }
        h3 {
            opacity: 0.5;
            text-transform: uppercase;
            font-size: 1em;
        }
    }
    .upgrade-text {
        width: 30%;
    }
    .image-upgrade {
        position: relative;
        width: 70%;

        .upgrade{
            width: 70%;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 10;
        }
        .youtube{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        .cross-3 {
            position: absolute;
            bottom: -77%;
            left: 68%;
        }
    }
}
</style>