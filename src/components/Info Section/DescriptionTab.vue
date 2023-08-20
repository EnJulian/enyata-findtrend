<script setup>
import CardComponent from "./CardComponent.vue";

</script>

<template>
  <div class="box">
    <div class="group">
      <div class="longtext-section">
        <p class="text-wrapper">Findtrend helps you to increase your</p>
        <p class="productivity-and">productivity and reduce your computer&#39;s</p>
        <p class="memory-load-an">
          <span class="span">memory load, </span>
          <span class="text-wrapper-2">an application that can </span>
        </p>
        <p class="div">fulfill your daily browsing needs.</p>
      </div>
    </div>
  </div>
  <div class="label">
    <p class="text-wrapper">Findtrend make +1000 Startup grow</p>
  </div>
<CardComponent/>

  
</template>

<style scoped>
.box {
  border: 0px none;
  height: 584px;
 margin-bottom: 250px;
}

.box .group {
  background-color: #ffffff;
  height: 584px;
  position: relative;
  left: 25%;
  top: 0;
}

.box .longtext-section {
  height: 304px;
  position: relative;
  top: 140px;
}

.box .text-wrapper {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 0;
}

.box .productivity-and {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 76px;
}

.box .memory-load-an {
  color: transparent;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 152px;

}

.box .span {
  color: #000000;
}

.box .text-wrapper-2 {
  color: #adadad;
}

.box .div {
  color: #adadad;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 228px;
}
.label {
  border: 0px none;
  
}

.label .text-wrapper {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  display: flex;
  letter-spacing: 0;
  line-height: normal;
  justify-content: center;
  text-align: center;

}



</style>
