<script setup>
import { ref, onMounted } from "vue";
import axios from "axios";

const user = ref();
onMounted(async () => {
    const data = await axios.get("/api/user");
    console.log(data);

});
</script>
<template>
    <div>
        <h1 class="text-3xl font-bold text-orange-500">Welcome to the Home Page</h1>
    
    </div>
  </template>
  
 
  