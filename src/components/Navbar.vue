<template>
  <nav
    class="bg-gradient-to-r from-white via-gray-50 to-white shadow-xl sticky top-0 z-50 border-b-2 border-blue-100 backdrop-blur-sm"
  >
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between h-20">
        <div class="flex items-center">
          <RouterLink to="/" class="flex-shrink-0 flex items-center group no-underline">
            <img
              src="/logo.jpg"
              alt="Manaram Security Logo"
              class="h-14 w-14 object-contain mr-4 rounded-lg shadow-lg group-hover:shadow-xl transition-all duration-300 group-hover:scale-105"
            />
            <div class="flex flex-col">
              <span
                class="text-2xl font-bold bg-gradient-to-r from-gray-900 via-blue-800 to-gray-900 bg-clip-text text-transparent"
                >Manaram Security</span
              >
              <span class="text-sm text-blue-600 font-medium">मानाराम सिक्यूरिटी</span>
            </div>
          </RouterLink>
        </div>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex items-center space-x-2">
          <RouterLink
            to="/"
            class="text-gray-700 hover:text-blue-600 hover:bg-blue-50 px-4 py-3 rounded-lg text-base font-medium transition-all duration-300 relative group no-underline"
            active-class="text-blue-600 font-semibold bg-blue-50"
          >
            Home
            <span
              class="absolute bottom-0 left-0 w-0 h-0.5 bg-saffron-500 group-hover:w-full transition-all duration-300"
            ></span>
          </RouterLink>
          <RouterLink
            to="/about"
            class="text-gray-700 hover:text-blue-600 hover:bg-blue-50 px-4 py-3 rounded-lg text-base font-medium transition-all duration-300 relative group no-underline"
            active-class="text-blue-600 font-semibold bg-blue-50"
          >
            About Us
            <span
              class="absolute bottom-0 left-0 w-0 h-0.5 bg-saffron-500 group-hover:w-full transition-all duration-300"
            ></span>
          </RouterLink>
          <RouterLink
            to="/services"
            class="text-gray-700 hover:text-blue-600 hover:bg-blue-50 px-4 py-3 rounded-lg text-base font-medium transition-all duration-300 relative group no-underline"
            active-class="text-blue-600 font-semibold bg-blue-50"
          >
            Services
            <span
              class="absolute bottom-0 left-0 w-0 h-0.5 bg-saffron-500 group-hover:w-full transition-all duration-300"
            ></span>
          </RouterLink>
          <RouterLink
            to="/industries"
            class="text-gray-700 hover:text-blue-600 hover:bg-blue-50 px-4 py-3 rounded-lg text-base font-medium transition-all duration-300 relative group no-underline"
            active-class="text-blue-600 font-semibold bg-blue-50"
          >
            Industries
            <span
              class="absolute bottom-0 left-0 w-0 h-0.5 bg-saffron-500 group-hover:w-full transition-all duration-300"
            ></span>
          </RouterLink>
          <RouterLink
            to="/contact"
            class="bg-gradient-to-r from-blue-600 to-blue-700 text-white px-6 py-3 rounded-lg text-base font-medium hover:from-blue-700 hover:to-blue-800 transition-all duration-300 shadow-lg hover:shadow-xl transform hover:scale-105 ml-4 no-underline"
          >
            Contact Us
          </RouterLink>
        </div>

        <!-- Mobile menu button -->
        <div class="md:hidden flex items-center">
          <button
            @click="mobileMenuOpen = !mobileMenuOpen"
            class="text-gray-700 hover:text-blue-600 focus:outline-none focus:text-blue-600"
          >
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path
                v-if="!mobileMenuOpen"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"
              />
              <path
                v-else
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              />
            </svg>
          </button>
        </div>
      </div>

      <!-- Mobile menu -->
      <div v-show="mobileMenuOpen" class="md:hidden">
        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3 border-t border-gray-200">
          <RouterLink
            to="/"
            @click="mobileMenuOpen = false"
            class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium no-underline"
            active-class="text-blue-600 font-semibold"
          >
            Home
          </RouterLink>
          <RouterLink
            to="/about"
            @click="mobileMenuOpen = false"
            class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium no-underline"
            active-class="text-blue-600 font-semibold"
          >
            About Us
          </RouterLink>
          <RouterLink
            to="/services"
            @click="mobileMenuOpen = false"
            class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium no-underline"
            active-class="text-blue-600 font-semibold"
          >
            Services
          </RouterLink>
          <RouterLink
            to="/industries"
            @click="mobileMenuOpen = false"
            class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium no-underline"
            active-class="text-blue-600 font-semibold"
          >
            Industries
          </RouterLink>
          <RouterLink
            to="/contact"
            @click="mobileMenuOpen = false"
            class="bg-blue-600 text-white block px-3 py-2 rounded-md text-base font-medium hover:bg-blue-700 no-underline"
          >
            Contact Us
          </RouterLink>
        </div>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { ref } from 'vue'

const mobileMenuOpen = ref(false)
</script>
