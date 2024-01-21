<template>
    <!-- Navbar -->
<nav>
    <div class="container">
      <!-- Logo -->
      <a href="#" class="logo">Logo</a>
    
      <!-- Navigation Links -->
      <div class="nav-links">
        <a href="#" class="nav-link">Home</a>
        <a href="#" class="nav-link">About</a>
        <a href="#" class="nav-link">Services</a>
        <a href="#" class="nav-link">Contact</a>
      </div>
    </div>
  </nav>
  
</template>
<style scoped>
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Navbar styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f3f4f6;
}

nav {
  background-color: #3b82f6;
  padding: 1rem;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  color: #ffffff;
  font-size: 1.5rem;
  font-weight: bold;
  text-decoration: none;
}

.nav-links {
  display: flex;
  align-items: center;
}

.nav-link {
  color: #ffffff;
  text-decoration: none;
  padding: 0.5rem;
  margin: 0.5rem;
  transition: background-color 0.3s, color 0.3s;
}

.nav-link:hover {
  background-color: #1e40af;
  color: #ffffff;
}
</style>