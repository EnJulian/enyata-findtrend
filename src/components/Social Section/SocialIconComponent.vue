<script setup>

</script>

<template>
 
  <div class="platform">
    <div class="platform-grid">
      <button  class="platform-image"><img src="../../assets/facebook.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/twitter.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/ball.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/pinterest.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/m.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/reddit.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/vk.svg" alt=""> </button>
      <button class="platform-image"><img src="../../assets/linkedin.svg" alt=""> </button>
      
    </div>
  </div>
 

</template>

<style scoped>
.platform{
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  
}

.platform-grid{
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  gap: 30px;
  margin: 0 auto;
  padding: 20px;
}

.platform-image{
  background-color: white;
  border-radius: 8px;
  padding: 20px 30px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  text-align: center;
}

button{
  border: none;
  cursor: pointer;
}
</style>
