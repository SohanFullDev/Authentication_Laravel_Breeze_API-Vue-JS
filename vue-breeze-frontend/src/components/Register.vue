<template>
    <div class="bg-white p-8 rounded-lg shadow-md w-96">
        <h2 class="text-2xl font-bold mb-6">Register</h2>
      
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
      
        <!-- Confirm Password Input -->
        <div class="mb-6">
          <label for="confirmPassword" class="block text-gray-700 text-sm font-semibold mb-2">Confirm Password:</label>
          <input type="password" id="confirmPassword" name="confirmPassword" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:border-blue-500" placeholder="Confirm your password">
        </div>
      
        <!-- Register Button -->
        <button class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600 focus:outline-none focus:ring focus:border-blue-300">Register</button>
      
        <!-- Login Link -->
        <div class="mt-4 text-center">
          <p class="text-sm text-gray-600">Already have an account? <a href="#" class="text-blue-500 hover:underline">Login</a></p>
        </div>
      </div>
</template>