<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from "./components/Hero Section/navbar.vue";
import Heroheader from "./components/Hero Section/heroheader.vue";
import Newtabs from "./components/Middle Section/newtabs.vue";
import DescriptionTab from "./components/Info Section/DescriptionTab.vue";
import SocialComponent from "./components/Social Section/SocialComponent.vue";
import PurchaseComponent from "./components/Purchase Section/PurchaseComponent.vue";
import FooterComponent from "./components/Footer Section/FooterComponent.vue";
import FooterBar from "./components/Footer Section/FooterBar.vue";
</script>

<template>
  <div class="hero-section">
    <div class="hero-bg">
    <navbar />
    </div>
    <heroheader/>
    <img class="btn-hero-socmed" alt="Btn hero socmed" src="src/assets/btn-hero-socmed.svg" />
  </div>
  
  <div class="middle-section">
    <div class="new-tab-bg">
      <newtabs/>
    </div>
  </div>

<div class="info-section">
  <DescriptionTab/>
</div>
  
  <div class="social-section">
    <SocialComponent/>
  </div>
  
  <div class="purchase-section">
    <PurchaseComponent/>
  </div>
  
  <div class="footer-section">
    <FooterComponent/>
  </div>
  
  <FooterBar/>
  
</template>

<style scoped>
.hero-section {
  border: 0px none;
  height: 900px;
  
}

.middle-section{
  border: 0px none;
  height: 900px;
}

.info-section{
  
}

.social-section{
}

.purchase-section{
  
}

.btn-hero-socmed{
  position: absolute;
  bottom: 300px;
  width: 50%;
  left: 27%;
  page-break-before: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
  page-break-after: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
  page-break-inside: avoid; /* or 'auto' */
}
.hero-bg{
  background-color: #000000;
  height: 900px;
  position: relative;
  top: 0;
  
}
.new-tab-bg{
  background-color: #a8ff35;
  height: 900px;
  position: relative;
  top: 0;

}

@media screen and (min-width: 1224px){
  .btn-hero-socmed{
    position: absolute;
    bottom: 300px;
    width: 60%;
    left: 22%;
    page-break-before: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
    page-break-after: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
    page-break-inside: avoid; /* or 'auto' */
  }
}

@media screen and (min-width: 320px) and (max-width: 480px){
  /* styles */
  .btn-hero-socmed{
    display: none;
  }


  .new-tab-bg{
    background-color: #a8ff35;
    height: 600px;
    position: relative;
    top: 0;

  }
}

/* Large screens ---------- */
@media screen and (min-width: 1824px){
  /* styles */
  .btn-hero-socmed{
    position: absolute;
    bottom: 300px;
    width: 50%;
    left: 26%;
    page-break-before: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
    page-break-after: auto; /* 'always,' 'avoid,' 'left,' 'inherit,' or 'right' */
    page-break-inside: avoid; /* or 'auto' */
  }
}

</style>
