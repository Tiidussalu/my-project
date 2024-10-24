<template>


  <nav class="bg-transparent border border-beige px-4 py-2 shadow-md mx-auto max-w-fit rounded-md mt-4">
    <div class="flex justify-between items-center space-x-8">
      <!-- Logo Section -->
      <div class="text-2xl font-bold text-beige">
        arik.
      </div>

      <!-- Navigation Links -->
      <div class="hidden md:flex space-x-6 text-sm font-medium text-beige">
        <a href="./FrontPage.vue" class="hover:text-white transition duration-300">SERVICES</a>
        <a href="#" class="hover:text-white transition duration-300">WORK</a>
        <a href="#" class="hover:text-white transition duration-300">ABOUT</a>
        <a href="#" class="hover:text-white transition duration-300">BLOG</a>

        <!-- Dropdown for Pages -->
        <div class="relative group">
          <a href="#" class="hover:text-white transition duration-300 flex items-center">
            PAGES
            <svg xmlns="http://www.w3.org/2000/svg" class="ml-1 h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
            </svg>
          </a>
          <!-- Dropdown Menu -->
          <div class="absolute left-0 mt-2 w-40 bg-black border border-gray-700 opacity-0 group-hover:opacity-100 transition-opacity duration-300 shadow-lg">
            <a href="#" class="block px-4 py-2 hover:bg-gray-700 text-beige">Page 1</a>
            <a href="#" class="block px-4 py-2 hover:bg-gray-700 text-beige">Page 2</a>
            <a href="#" class="block px-4 py-2 hover:bg-gray-700 text-beige">Page 3</a>
          </div>
        </div>
      </div>

      <!-- Let's Talk Button -->
      <button class="bg-beige text-black font-semibold px-4 py-2 rounded-lg hover:bg-opacity-90 transition duration-300">
        LET'S TALK
      </button>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style scoped>
/* Custom Colors */
.text-beige {
  color: #e3dac9;
}
.bg-beige {
  background-color: #e3dac9;
}

/* Style the shadow effect for the navbar */
.shadow-md {
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
}
</style>
