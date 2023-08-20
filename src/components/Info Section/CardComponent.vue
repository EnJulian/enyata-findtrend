<script setup>

</script>

<template>
  <div class="image-grid">
    <div class="card-grid">
      <div class="card"><img src="../../assets/microsoft.svg" alt="Image 1"></div>
      <div class="card"><img src="../../assets/allianz.svg" alt="Image 2"></div>
      <div class="card"><img src="../../assets/upwork.svg" alt="Image 3"></div>
      <div class="card"><img src="../../assets/volvo.svg" alt="Image 4"></div>
      <div class="card"><img src="../../assets/grab.svg" alt="Image 5"></div>
      <div class="card"><img src="../../assets/verizon.svg" alt="Image 6"></div>
      <div class="card"><img src="../../assets/coinbase.svg" alt="Image 7"></div>
      <div class="card"><img src="../../assets/expedia.svg" alt="Image 8"></div>
      <div class="card"><img src="../../assets/airtable.svg" alt="Image 9"></div>
      <div class="card"><img src="../../assets/magento.svg" alt="Image 10"></div>
      <div class="card"><img src="../../assets/carrera.svg" alt="Image 11"></div>
      <div class="card"><img src="../../assets/bonanza.svg" alt="Image 12"></div>
      <div class="card"><img src="../../assets/wetransfer.svg" alt="Image 13"></div>
      <div class="card"><img src="../../assets/suzuki.svg" alt="Image 14"></div>
      <div class="card"><img src="../../assets/algolia.svg" alt="Image 15"></div>
      <div class="card"><img src="../../assets/heineken.svg" alt="Image 16"></div>
      
     
    </div>
  </div>
</template>

<style scoped>
.image-grid {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  
  background-color: white;  
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 50px;
  margin: 0 auto;
  padding: 20px;
}

.card {
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 30px 50px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  text-align: center;
}

</style>
