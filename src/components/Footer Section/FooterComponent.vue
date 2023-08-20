<script setup>

import FooterBar from "./FooterBar.vue";
</script>

<template>
 
  <div class="box">
    <div class="group">
      <div class="overlap-group">
        <div class="frame">
          <div class="text-wrapper">Join Now</div>
        </div>
        <div class="div">more trending topics</div>
        <p class="p">Join us on email for</p>
      </div>
    </div>
  </div>
 
  

</template>

<style scoped>
.box {
  border: 0px none;
  height: 539px;
}

.box .group {
  height: 539px;

}

.box .overlap-group {
  background-color: #a8ff35;
  height: 539px;
  position: relative;
}

.box .frame {
  align-items: center;
  background-color: #000000;
  border-radius: 40px;
  display: flex;
  gap: 10px;
  justify-content: center;
  left: 45%;
  padding: 16px 32px;
  position: absolute;
  top: 402px;
  width: 180px;
}

.box .text-wrapper {
  color: #ffffff;
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

.box .div {
  color: #87d322;
  font-family: "Effra-Heavy", Helvetica;
  font-size: 72px;
  font-weight: 400;
  left: 34%;
  letter-spacing: 0;
  line-height: 80.6px;
  position: absolute;
  text-align: center;
  top: 260px;
  width: 740px;
}

.box .p {
  color: #000000;
  font-family: "Effra-Heavy", Helvetica;
  font-size: 72px;
  font-weight: 400;
  left: 34%;
  letter-spacing: 0;
  line-height: 80.6px;
  position: absolute;
  text-align: center;
  top: 100px;
  width: 740px;
}

</style>
