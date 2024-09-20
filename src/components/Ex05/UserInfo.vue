<template>
    <div>
      <h1>Ex05</h1>
      <ul>
        <h2>Thông tin người dùng</h2>
        <li>Họ và Tên: {{ user.userName }}</li>
        <li>Giới tính: {{ user.gender }}</li>
        <li>Ngày sinh: {{ user.birth }}</li>
        <li>Email: {{ user.email }}</li>
        <li>Địa Chỉ: {{ user.address }}</li>
      </ul>
    </div>
  </template>
  
  <script setup>
  const user = {
    userName: "Dương Sỹ Hiệp",
    gender: "Nam",
    birth: "04/09/2005",
    email: "duonghiep0904@gmail.com",
    address: "Thanh Oai, Ha Noi",
  };
  </script>
  
  <style >
  </style>
  