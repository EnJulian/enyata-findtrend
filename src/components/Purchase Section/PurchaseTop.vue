<script setup>

</script>

<template>
 
  <div class="box">
    <div class="group">
      <img class="img" alt="Group" src="src/assets/group-427321660.svg" />
      <div class="text-wrapper">Yearly</div>
      <label class="toggle">
        <input type="checkbox">
        <span class="slider"></span>
      </label>
      <div class="div">Monthly</div>
      <div class="text-wrapper-2">Get your best deal</div>
    </div>
  </div>
  
</template>

<style scoped>
.box {
  border: 0px none;
  height: 173px;
  position: relative;
  top: 300px;
  left: 25%;
}

.box .group {
  height: 173px;
  left: 0;
  top: 0;
  width: 1166px;
}

.box .img {
  height: 67px;
  left: 762px;
  position: absolute;
  top: 106px;
  width: 88px;
}

.box .text-wrapper {
  color: #f5f5f5;
  font-family: "Inter-Medium", Helvetica;
  font-size: 24px;
  font-weight: 500;
  left: 667px;
  letter-spacing: 0;
  line-height: normal;
  opacity: 0.5;
  position: absolute;
  top: 127px;
}

.box .toggle {
  left: 539px;
  position: absolute;
  top: 116px;
  width: 60px;
  height: 34px;
  
}

.box .div {
  color: #ffffff;
  font-family: "Inter-Medium", Helvetica;
  font-size: 24px;
  font-weight: 500;
  left: 421px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 127px;
}

.box .text-wrapper-2 {
  color: #ffffff;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 1160px;
}




.box.toggle input {
  display: none;
}

.box .slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  transition: 0.4s;
  border-radius: 34px;
}

.box .slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  transition: 0.4s;
  border-radius: 50%;
}

input:checked + .slider {
  background-color: #A8FF35;
}

input:checked + .slider:before {
  transform: translateX(26px);
}
</style>
