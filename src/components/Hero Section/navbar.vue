<script setup>
import { ref } from 'vue'
</script>

<template>

  <div class="box-mobile">
    <div class="group">
      <img class="vector" alt="Vector" src="../../assets/findtrend.svg" />
      <img class="icon" alt="Icon" src="../../assets/hamburger.svg" />
    </div>
  </div>


  <div class="navbar">
    <div class="nav-btn-wrapper">
      <div class="register">
        <div class="text-wrapper">Register</div>
      </div>
      <div class="div">Login</div>
    </div>
    <div class="div-2">
      <span class="text-wrapper-2">About</span>
      <span class="text-wrapper-2">How it work</span>
      <span class="text-wrapper-2">Pricing</span>
      <span class="text-wrapper-2">Solution</span>
      <span class="text-wrapper-2">Features</span>
    </div>
    <div class="logo">
      <div class="text-wrapper-3">Findtrend</div>
      <div class="overlap-group">
        <div class="ellipse" />
        <img class="vector" alt="Vector" src="../../assets/findtrend.svg" />
      </div>
    </div>
  </div>
  

</template>

<style scoped>
.box-mobile{
  display: none;
}
.navbar {
  border: 1px none;
  
}

.navbar .nav-btn-wrapper {
  height: 42px;
  left: 80%;
  position: absolute;
  top: 28px;
  width: 215px;
}

.navbar .register {
  align-items: center;
  background-color: #ffffff;
  border-radius: 40px;
  display: inline-flex;
  gap: 10px;
  justify-content: space-between;

  left: 30%;
  padding: 12px 32px;
  position: absolute;
  top: 0;
}

.navbar .text-wrapper {
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

.navbar .div {
  color: #ffffff;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 18px;
  position: absolute;
  text-align: center;
  top: 12px;
  white-space: nowrap;
}

.navbar .div-2 {
  height: 42px;
  left: 40%;
  position: absolute;
  top: 40px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.navbar .text-wrapper-2 {
  color: #ffffff;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  letter-spacing: 0;
  line-height: 18px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  margin-left: 20px;
  white-space: nowrap;
  width: fit-content;
}

.navbar .logo {
  height: 41px;
  position: absolute;
  top: 29px;
  left: 10%;
  width: 170px;
}

.navbar .text-wrapper-3 {
  color: #ffffff;
  font-family: "Inter-Bold", Helvetica;
  font-size: 24px;
  font-weight: 700;
  left: 35%;
  letter-spacing: 0;
  line-height: 24px;
  position: absolute;
  text-align: center;
  top: 7px;
  white-space: nowrap;
}

.navbar .overlap-group {
  height: 40px;
  position: absolute;
  top: 0;
  width: 40px;
}

.navbar .ellipse {
  background-color: #000000;
  border-radius: 16px;
  height: 32px;
  position: absolute;
  top: 4px;
  width: 32px;
}

.navbar .vector {
  height: 40px;
  position: absolute;
  top: 0;
  width: 40px;
}

@media screen and (min-width: 1224px){
  .navbar .logo {
    height: 41px;
    position: absolute;
    top: 29px;
    left: 5%;
    width: 170px;
  }

  .navbar .div-2 {
    height: 42px;
    left: 35%;
    position: absolute;
    top: 40px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
}

@media screen and (min-width: 320px) and (max-width: 480px){
  /* styles */
  .navbar{
    display: none;
  }
 
  .box-mobile {
    display: block;
    border: 0px none;
    height: 88px;
    bottom: 1000px;
    position: absolute;
    width: 100%;
  }

  .box-mobile .group {
    height: 88px;
    left: 0;
    position: absolute;
    top: 0;
    width: 375px;
  }

  .box-mobile .vector {
    height: 40px;
    left: 7%;
    position: absolute;
    top: 24px;
    width: 40px;
  }

  .box-mobile .icon {
    height: 24px;
    left: 91%;
    position: absolute;
    top: 32px;
    width: 24px;
  }


}


/* Large screens ---------- */
@media screen and (min-width: 1824px){
  /* styles */
  .navbar .nav-btn-wrapper {
    height: 42px;
    left: 88%;
    position: absolute;
    top: 28px;
    width: 215px;
  }
  .navbar .div-2 {
    height: 42px;
    left: 40%;
    position: absolute;
    top: 40px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }


}

</style>
