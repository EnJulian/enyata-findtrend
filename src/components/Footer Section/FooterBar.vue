<script setup>

</script>

<template>
  
  <div class="box">
    <div class="group">
      <div class="div">
        <div class="navbar">
          <div class="text-wrapper">Privacy Policy</div>
          <div class="text-wrapper">Terms and Conditions</div>
          <div class="text-wrapper">Contact Us</div>
          <div class="text-wrapper">Careers</div>
        </div>
        <div class="frame">
          <div class="text-wrapper-2">Findtrend</div>
          <div class="overlap-group">
            <div class="ellipse" />
            <img class="vector" alt="Vector" src="src/assets/findtrend2.svg" />
          </div>
        </div>
      </div>
    </div>
  </div>
  

</template>

<style scoped>
.box {
  border: 0px none;
  height: 100px;
  width: 1440px;
}

.box .group {
  background-color: #ffffff;
  height: 100px;

  width: 100%;
}

.box .div {
  height: 41px;
  left: 80px;
  position: relative;
  top: 29px;
  width: 1260px;
}

.box .navbar {
  align-items: flex-start;
  display: inline-flex;
  gap: 40px;
  left: 120%;
  position: absolute;
  top: 12px;
}

.box .text-wrapper {
  color: #000000;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 18px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.box .frame {
  height: 41px;
  left: 0;
  position: absolute;
  top: 0;
  width: 170px;
}

.box .text-wrapper-2 {
  color: #000000;
  font-family: "Inter-Bold", Helvetica;
  font-size: 24px;
  font-weight: 700;
  left: 51px;
  letter-spacing: 0;
  line-height: 24px;
  position: absolute;
  text-align: center;
  top: 7px;
  white-space: nowrap;
}

.box .overlap-group {
  height: 40px;
  left: 1px;
  position: absolute;
  top: 0;
  width: 40px;
}

.box .ellipse {
  background-color: #ffffff;
  border-radius: 16px;
  height: 32px;
  left: 4px;
  position: absolute;
  top: 4px;
  width: 32px;
}

.box .vector {
  height: 40px;
  left: 0;
  position: absolute;
  top: 0;
  width: 40px;
}

</style>
