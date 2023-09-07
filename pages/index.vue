<template>


   <Navbar/>
   <Mainsection/>
   <Card/>
   <Information/>
   <Pricing/>
   <Footer/>
  
  </template>
  
  <script setup>
  import { onMounted } from 'vue'
  import { initFlowbite } from 'flowbite'
  
  
  onMounted(() => {
      initFlowbite();
  })
  </script>
