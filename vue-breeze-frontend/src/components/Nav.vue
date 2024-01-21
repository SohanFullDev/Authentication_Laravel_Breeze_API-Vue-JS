<template>

    <nav class="bg-blue-500 p-4">
        <div class="container mx-auto flex items-center justify-between">
          <!-- Logo -->
          <a href="#" class="text-white text-lg font-bold">Logo</a>
      
          <!-- Navigation Links -->
          <div class="flex items-center space-x-4">
            <router-link :to="{name: 'Home'}" class="text-white hover:underline">Home</router-link>
            <router-link :to="{name: 'Login'}"  class="text-white hover:underline">Login</router-link>
            <router-link :to="{name: 'Register'}" class="text-white hover:underline">Register</router-link>
            <a href="#" class="text-white hover:underline">Contact</a>
          </div>
        </div>
      </nav>
        
</template>