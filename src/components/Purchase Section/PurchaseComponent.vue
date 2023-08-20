<script setup>

import PurchaseTop from "./PurchaseTop.vue";
</script>

<template>
  <PurchaseTop/>
  <div class="cards-container">
   
    <div class="box">
      <div class="personal">
        <div class="overlap">
          <div class="text-wrapper">Personal</div>
          <p class="div">Special first packet for all</p>
          <div class="group">
            <div class="text-wrapper-2">$8</div>
            <div class="text-wrapper-3">/Month</div>
          </div>
          <div class="group-2">
            <p class="p">Up to 5 page each group</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-3">
            <p class="p">Up to 10 group page</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-4">
            <p class="p">5 Days group page saved</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="overlap-group-wrapper">
            <button class="overlap-group">
              Start Free Trial
            </button>
          </div>
          <div class="card-line"></div>
        </div>
      </div>
    </div>


    <div class="box">
      <div class="personal">
        <div class="overlap">
          <div class="text-wrapper">Regular</div>
          <p class="div">Recommended for personal pro</p>
          <div class="group">
            <div class="text-wrapper-2">$20</div>
            
            <div class="text-wrapper-3-new">/Month</div>
          </div>
          <div class="group-2">
            <p class="p">Up to 15 page each group</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-3">
            <p class="p">Download page up to 20 page</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-4">
            <p class="p">Up to 10 group page</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-5">
            <p class="p">15 Days group page saved</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="overlap-group-wrapper">
            <button class="overlap-group">
              Start Free Trial
            </button>
          </div>
          <div class="card-line"></div>
        </div>
      </div>
    </div>


    <div class="box">
      <div class="personal">
        <div class="overlap">
          <div class="text-wrapper">Premium</div>
          <p class="div">Packet for Startup & Company</p>
          <div class="group">
            <div class="text-wrapper-2">$48</div>
            <div class="text-wrapper-3-new">/Month</div>
          </div>
          <div class="group-2">
            <p class="p">Unlimited group pages</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-3">
            <p class="p">Unlimited download page</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-4">
            <p class="p">Unlimited page each group</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-5">
            <p class="p">Customize sorting group pages</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
          <div class="group-6">
            <p class="p">Customize group page name</p>
            <img class="frame" alt="Frame" src="src/assets/Frame%2029.svg" />
          </div>
         
          <div class="overlap-group-wrapper">
            <button class="overlap-group">
              Start Free Trial
            </button>
          </div>
          <div class="card-line"></div>
        </div>
      </div>
    </div>

    

    
    <!-- ... Repeat for other cards ... -->
  </div>
  
</template>

<style scoped>
.cards-container {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 400px;
  padding-bottom: 200px;
  background-color: black;
}



.box {
  border: 0px none;
  height: 640px;
  width: 360px;
  margin: 0 20px;
}

.box .personal {
  height: 640px;
  
  top: 0;
  width: 364px;
}

.box .overlap {
  background-color: #fafafa;
  border-radius: 16px;
  height: 640px;
  position: relative;
  width: 360px;
}
.box .overlap:hover{
  background-color: #a8ff35;
  cursor: pointer;
}

.box .text-wrapper {
  color: #000000;
  font-family: "Effra-Medium", Helvetica;
  font-size: 36px;
  font-weight: 500;
  left: 32px;
  letter-spacing: 0;
  line-height: 36px;
  position: absolute;
  top: 32px;
  white-space: nowrap;
}

.box .div {
  color: #000000;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  left: 32px;
  letter-spacing: 0;
  line-height: 18px;
  position: absolute;
  top: 76px;
  white-space: nowrap;
}

.box .group {
  height: 64px;
  left: 32px;
  position: absolute;
  top: 158px;
  width: 140px;
}

.box .text-wrapper-2 {
  color: #000000;
  font-family: "Effra-Medium", Helvetica;
  font-size: 64px;
  font-weight: 500;
  left: 0;
  letter-spacing: 0;
  line-height: 64px;
  position: absolute;
  top: 0;
  white-space: nowrap;
}

.box .text-wrapper-3 {
  color: #000000;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  left: 50%;
  letter-spacing: 0;
  line-height: 18px;
  position: absolute;
  top: 40px;
  white-space: nowrap;
}
.box .text-wrapper-3-new {
  color: #000000;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  left: 75%;
  letter-spacing: 0;
  line-height: 18px;
  position: absolute;
  top: 40px;
  white-space: nowrap;
}

.box .group-2 {
  height: 24px;
  left: 32px;
  position: absolute;
  top: 254px;
  width: 221px;
}

.box .p {
  color: #000000;
  font-family: "Effra-Regular", Helvetica;
  font-size: 18px;
  font-weight: 400;
  left: 32px;
  letter-spacing: 0;
  line-height: 18px;
  position: absolute;
  
  white-space: nowrap;
}

.box .frame {
  height: 24px;
  position: absolute;
  top: 15px;
  width: 24px;
}

.box .group-3 {
  height: 24px;
  left: 32px;
  position: absolute;
  top: 302px;
  width: 190px;
}

.box .group-4 {
  height: 24px;
  left: 32px;
  position: absolute;
  top: 350px;
  width: 226px;
}
.box .group-5{
  height: 24px;
  left: 32px;
  position: absolute;
  top: 400px;
  width: 226px;
}
.box .group-6{
  height: 24px;
  left: 32px;
  position: absolute;
  top: 450px;
  width: 226px;
}

.box .overlap-group-wrapper {
  height: 58px;
  left: 32px;
  position: absolute;
  top: 558px;
  width: 298px;
  
}
.box .overlap-group:hover {
  background-color: #000000;
  color: white;
  cursor: pointer;
}

.box .overlap-group {
  border: none;
  background-color: #a8ff35;
  border-radius: 29px;
  height: 58px;
  position: relative;
  width: 296px;
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: 25.2px;
  text-align: center;
  white-space: nowrap;
  
}

.box .text-wrapper-4 {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 18px;
  font-weight: 700;
  left: 89px;
  letter-spacing: 0;
  line-height: 25.2px;
  position: absolute;
  text-align: center;
  top: 16px;
  white-space: nowrap;
}


.box .card-line{
  height: 1px;
  left: 32px;
  object-fit: cover;
  position: absolute;
  top: 125px;
  width: 296px;
 
  background-color: #ccc;
  margin-bottom: 32px;
}



</style>
