<template>
     
     <div class="bg-white p-8 rounded-lg shadow-md w-96">
          <h2 class="text-2xl font-bold mb-6">Login</h2>
        
          <!-- Email Input -->
          <div class="mb-4">
            <label for="email" class="block text-gray-700 text-sm font-semibold mb-2">Email:</label>
            <input type="email" id="email" name="email" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your email">
          </div>
        
          <!-- Password Input -->
          <div class="mb-4">
            <label for="password" class="block text-gray-700 text-sm font-semibold mb-2">Password:</label>
            <input type="password" id="password" name="password" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Enter your password">
          </div>
        
          <!-- Forgot Password Link -->
          <div class="mb-4 text-right">
            <a href="#" class="text-blue-500 hover:underline text-sm">Forgot Password?</a>
          </div>
        
          <!-- Login Button -->
          <button class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600 focus:outline-none focus:ring focus:border-blue-300">Login</button>
        
          <!-- Sign Up Link -->
          <div class="mt-4 text-center">
            <p class="text-sm text-gray-600">Not a member yet? <a href="#" class="text-blue-500 hover:underline">Sign up</a></p>
          </div>
        </div>
</template>