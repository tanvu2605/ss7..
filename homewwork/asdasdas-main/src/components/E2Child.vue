<template>
    <div>
      <h3>Dữ liệu trong component con</h3>
      <ul>
        <li>id: {{ data.data.id }}</li>
        <li>Product name: {{ data.data.name }}</li>
        <li>price: {{ data.data.price }}</li>
        <li>quantity: {{ data.data.quantity }}</li>
      </ul>
    </div>
  </template>
  <script setup>
  const data = defineProps(["data"]);
  </script>
  <style></style>