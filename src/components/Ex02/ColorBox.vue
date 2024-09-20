<template>
    <div>
        <h1>Ex02</h1>
      <div class="container">
        <p id="Red">Box</p>
        <p id="Blue">Box</p>
        <p id="Green">Box</p>
      </div>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style>
  .container {
    display: flex;
    gap: 50px;
  }
  
  p {
    width: 200px;
    height: 200px;
    display: flex; 
    justify-content: center;
    align-items: center; 
    color: white;
  }
  
  #Red {
    background-color: red;
  }
  #Blue {
    background-color: blue;
  }
  #Green {
    background-color: green;
  }
  </style>
  