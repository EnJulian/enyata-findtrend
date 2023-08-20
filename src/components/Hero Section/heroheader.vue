<script setup>

</script>

<template>
 
  <div class="mobile-box">
    <div class="mobile-group">
      <div class="mobile-div">
        <div class="mobile-text-wrapper">Find the trends!</div>
        <div class="mobile-text-wrapper-2">Minimize your tabs.</div>
      </div>
      <p class="mobile-don-t-let-your">
        Don’t let your computer memories consumes all of those browser tabs. <br />
        Findtrend let you gathers all of your favorite website into one place.
      </p>
      <div class="mobile-get-started">
        <div class="mobile-text-wrapper-3">Get Started 🔥</div>
      </div>
    </div>
  </div>
  <img class="mobile-tags" alt="tags" src="src/assets/mobile-tags.svg" />




  <div class="box">
    <div class="hero-content-wrapper">
      <div class="img-hero">
        <div class="overlap-group">
          <img class="arrow" alt="Arrow" src="src/assets/arrow-03.svg" />
          <img class="all-research-start" alt="All research start" src="src/assets/all-research-start-from-here.svg" />
          
        </div>
      </div>
      <div class="get-started">
        <div class="text-wrapper">Get Started 🔥</div>
      </div>
      <p class="don-t-let-your">
        Don’t let your computer memories consumes all of those browser tabs. <br />
        Findtrend let you gathers all of your favorite website into one place.
      </p>
      <div class="div">Find the trends!</div>
      <div class="text-wrapper-2">Minimize your tabs.</div>
    </div>
  </div>
  

</template>

<style scoped>
.mobile-box{
  display: none;
}
.mobile-tags{
  display: none;
}
.box {
  border: 0px none;
  height: 337.63px;
  overflow-x: hidden;
  position: absolute;
  bottom: 600px;
  left: 35%;
  width: 100%;
}

.box .hero-content-wrapper {
  height: 338px;
  position: absolute;
  top: 0;
  width: 706px;
}

.box .img-hero {
  height: 70px;
  left: 66%;
  position: absolute;
  top: 268px;
  width: 101px;
}


.box .overlap-group {
  height: 69px;
  position: relative;
  top: 1px;
  width: 97px;
}

.box .arrow {
  height: 38px;
  position: absolute;
  top: 31px;
  width: 42px;
}

.box .all-research-start {
  height: 34px;
  position: absolute;
  top: 0;
  width: 90px;
}

.box .get-started {
  align-items: center;
  background-color: #a8ff35;
  border-radius: 40px;
  display: inline-flex;
  justify-content: center;
  left: 36%;
  padding: 16px 32px;
  position: absolute;
  top: 280px;
}

.box .text-wrapper {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 25.2px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.box .don-t-let-your {
  color: #8b8b8b;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  left: 3%;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 27px;
  position: absolute;
  text-align: center;
  top: 186px;
  width: 666px;
}

.box .div {
  color: #ffffff;
  font-family: "Effra-Heavy", Helvetica;
  font-size: 72px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 80.6px;
  position: absolute;
  text-align: center;
  top: 81px;
  width: 700px;
}

.box .text-wrapper-2 {
  color: #ffffff;
  font-family: "Effra-Heavy", Helvetica;
  font-size: 72px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 80.6px;
  position: absolute;
  text-align: center;
  top: 0;
  width: 700px;
}

@media screen and (min-width: 1224px){
  .box {
    border: 0px none;
    height: 337.63px;
    overflow-x: hidden;
    position: absolute;
    bottom: 550px;
    left: 27%;
    width: 100%;
  }
}


@media screen and (min-width: 320px) and (max-width: 480px){
  /* styles */
  .box{
    display: none;
  }
 

  .mobile-box {
    display: block;
    border: 0px none;
    height: 256px;
    bottom: 650px;
    left: 11%;
    overflow-x: hidden;
    position: absolute;
    width: 100%;
  }

  .mobile-tags{
    display: block;
    position: absolute;
    bottom: 250px;
    left: 13%;
  }

  .mobile-box .mobile-div {
    height: 80px;
    position: absolute;
    top: 0;
    width: 324px;
  }

  .mobile-box .mobile-text-wrapper {
    color: #ffffff;
    font-family: "Effra-Heavy", Helvetica;
    font-size: 36px;
    font-weight: 400;
    left: 30px;
    letter-spacing: 0;
    line-height: 40.3px;
    position: absolute;
    text-align: center;
    top: 40px;
    white-space: nowrap;
  }

  .mobile-box .mobile-text-wrapper-2 {
    color: #ffffff;
    font-family: "Effra-Heavy", Helvetica;
    font-size: 36px;
    font-weight: 400;
    left: 0;
    letter-spacing: 0;
    line-height: 40.3px;
    position: absolute;
    text-align: center;
    top: 0;
    white-space: nowrap;
  }

  .mobile-box .mobile-don-t-let-your {
    color: #8b8b8b;
    font-family: "Effra-Regular", Helvetica;
    font-size: 14px;
    font-weight: 400;
    left: 17px;
    letter-spacing: 0;
    line-height: 21px;
    position: absolute;
    text-align: center;
    top: 96px;
    width: 286px;
  }

  .mobile-box .mobile-get-started {
    align-items: center;
    background-color: #a8ff35;
    border-radius: 40px;
    display: inline-flex;
    gap: 10px;
    justify-content: center;
    left: 90px;
    padding: 12px 24px;
    position: absolute;
    top: 212px;
  }

  .mobile-box .mobile-text-wrapper-3 {
    color: #000000;
    font-family: "Effra-Bold", Helvetica;
    font-size: 14px;
    font-weight: 700;
    letter-spacing: 0;
    line-height: 19.6px;
    margin-top: -1px;
    position: relative;
    text-align: center;
    white-space: nowrap;
    width: fit-content;
  }

}

/* Large screens ---------- */
@media screen and (min-width: 1824px){
  /* styles */
  .box {
    border: 0px none;
    height: 337.63px;
    overflow-x: hidden;
    position: absolute;
    bottom: 600px;
    left: 35%;
    width: 100%;
  }
}
</style>
