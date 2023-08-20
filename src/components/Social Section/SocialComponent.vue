<script setup>
import SocialIconComponent from "./SocialIconComponent.vue";
import FeedComponent from "./FeedComponent.vue";
import SocialButton from "./SocialButton.vue";
</script>

<template>
 
  <div class="label">
    <p class="text-wrapper">All platform connect to Findtrend</p>
  </div>
  
  <div class="socials">
    <SocialIconComponent/>
  </div>
    <FeedComponent/>

  <div class="socialButton">
  <SocialButton/>
  </div>
 

</template>

<style scoped>
.label {
  border: 0px none;
  height: 76px;
  margin-top: 300px;
  display: flex;
  justify-content: center;
}

.label .text-wrapper {
  color: #000000;
  font-family: "Effra-Bold", Helvetica;
  font-size: 64px;
  font-weight: 700;
  letter-spacing: 0;
  line-height: normal;
  text-align: center;
  top: 0;
  white-space: nowrap;
}
.socials{
  display: flex;
  
  gap: 150px;
  justify-content: center;
  margin-top: 120px;
}

.socialButton{
  display: flex;
  justify-content: center;
  padding: 40px;
}
button{
  padding: 20px;
  border-radius: 40px;
  cursor: pointer;
}

</style>
