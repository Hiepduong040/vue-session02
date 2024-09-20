<template>
    <div>
      <h1>Ex06</h1>
      <ul>
        <li>Họ và Tên: {{ formatName(user) }}</li>
      </ul>
    </div>
  </template>
  
  <script setup>
  const user = {
    firstName: "Dương Sỹ",
    lastName: "Hiệp"
  };
  
  const formatName = (user) => {
    return `${user.firstName} ${user.lastName}`;
  };
  </script>
  
  <style >
  </style>
  