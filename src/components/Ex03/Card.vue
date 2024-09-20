<template>
  <div>
    <h1>Ex03</h1>

    <div class="card">
      <div class="image">Image</div>
      <div class="title">Title</div>
      <button class="addCard">Add to card</button>
    </div>
  </div>
</template>
  
  <script setup>
</script>
  
  <style scoped>
.card {
  width: 200px;
  border-radius: 10px;
  border: 1px solid #ccc;
  text-align: center;
  font-family: Arial, sans-serif;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
}

.image {
  background-color: #999;
  height: 150px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 18px;
}

.title {
  font-size: 18px;
  font-weight: bold;
  padding: 15px 0;
}

.addCard {
  background-color: #f0f0f0;

  border: 1px solid #ccc;
  padding: 10px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
</style>
  