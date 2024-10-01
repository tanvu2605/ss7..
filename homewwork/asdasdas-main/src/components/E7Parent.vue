<template>
    <div>
      <MessageChildren @messeage="handleMessage"/>
    </div>
  </template>
  
  <script setup>
  import E7Child from './E7Child.vue';
  const handleMessage =()=>{
      alert("welcome")
  }
  
  </script>
  
  <style>
  
  </style>