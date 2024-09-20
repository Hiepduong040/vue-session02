<template>
  <div>
    <h1>Ex04</h1>
    <h2>Danh sách kết quả</h2>
    <input v-model="num1" type="number" placeholder="number1" />
    <input v-model="num2" type="number" placeholder="number2" />
    <ul>
      <li>{{ num1 }} + {{ num2 }} = {{ add(num1, num2) }}</li>
      <li>{{ num1 }} - {{ num2 }} = {{ subtract(num1, num2) }}</li>
      <li>{{ num1 }} * {{ num2 }} = {{ multiply(num1, num2) }}</li>
      <li>{{ num1 }} / {{ num2 }} = {{ divide(num1, num2) }}</li>
    </ul>
  </div>
</template>
  
<script setup>
import { ref } from "vue";
const num1 = ref(10);
const num2 = ref(10);

const add = (a, b) => a + b;
const subtract = (a, b) => a - b;
const multiply = (a, b) => a * b;
const divide = (a, b) => a / b;
</script>
  
  <style >
</style>
  