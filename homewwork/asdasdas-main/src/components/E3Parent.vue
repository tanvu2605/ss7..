<template>
    <div>
      <p>Count :{{count}}</p>
      <E3Child @-increase="handleIncrease"/>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  import E3Child from './E3Child.vue';
  let count = ref(0);
  const handleIncrease =()=>{
      count.value++
  }
  
  </script>
  
  <style>
  
  </style>