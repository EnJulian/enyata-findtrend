<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from "./components/navbar.vue";
import Heroheader from "./components/heroheader.vue";
import Newtabs from "./components/newtabs.vue";
</script>

<template>
  <div class="hero-section">
    <div class="hero-bg" />
    <img class="btn-hero-socmed" alt="Btn hero socmed" src="src/assets/btn-hero-socmed.svg" />
    <navbar />
    <heroheader/>
  </div>
  
  <div class="new-tab-section">
    <div class="new-tab-bg">
      <newtabs/>
    </div>
  </div>


  
</template>

<style scoped>
.hero-section {
  border: 0px none;
  height: 900px;
  
}

.new-tab-section{
  border: 0px none;
  height: 900px;
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
