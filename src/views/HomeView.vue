<template>
  <div>
    <!-- Hero Section -->
    <section class="relative bg-gradient-to-br from-blue-900 via-blue-800 to-blue-900 text-white">
      <div class="absolute inset-0 bg-black opacity-50"></div>
      <div
        class="absolute inset-0 bg-cover bg-center"
        style="background-image: url('/imgs/banner.jpg')"
      ></div>
      <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24 md:py-32">
        <div class="text-center">
          <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
            Professional Industrial Security Services
            <br />
            <span class="text-3xl md:text-5xl text-blue-200"
              >Trusted Manpower Solutions for Indian Industries</span
            >
          </h1>
          <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto text-gray-200">
            Comprehensive security manpower services for factories, industrial facilities, and
            commercial establishments across India with trained security guards and advanced
            monitoring.
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <RouterLink
              to="/contact"
              class="bg-saffron-600 hover:bg-saffron-700 text-white px-8 py-4 rounded-lg text-lg font-semibold transition-all duration-300 transform hover:scale-105 shadow-lg"
            >
              Get Free Security Consultation
            </RouterLink>
            <RouterLink
              to="/services"
              class="border-2 border-white text-white hover:bg-white hover:text-blue-900 px-8 py-4 rounded-lg text-lg font-semibold transition-all duration-300"
            >
              Our Security Services
            </RouterLink>
          </div>
        </div>
      </div>
    </section>

    <!-- Indian Security Excellence Section -->
    <section class="py-16 bg-gradient-to-r from-saffron-50 to-green-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
            Industrial Security Manpower Excellence
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Professional security guard services for Indian industries with trained personnel,
            modern equipment, and 24/7 monitoring solutions.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
          <div class="text-center">
            <div class="relative mb-6">
              <img
                src="/imgs/7.jpg"
                alt="Professional Security Guard at Industrial Gate"
                class="rounded-lg shadow-xl mx-auto w-full h-64 object-cover"
              />
              <div
                class="absolute -bottom-4 left-1/2 transform -translate-x-1/2 bg-saffron-600 text-white px-4 py-2 rounded-full text-sm font-semibold"
              >
                Trained Security Guards
              </div>
            </div>
          </div>

          <div class="text-center">
            <div class="relative mb-6">
              <img
                src="/imgs/safety.jpg"
                alt="Industrial Facility Security"
                class="rounded-lg shadow-xl mx-auto w-full h-64 object-cover"
              />
              <div
                class="absolute -bottom-4 left-1/2 transform -translate-x-1/2 bg-blue-600 text-white px-4 py-2 rounded-full text-sm font-semibold"
              >
                Factory & Industrial Security
              </div>
            </div>
          </div>

          <div class="text-center">
            <div class="relative mb-6">
              <img
                src="/imgs/Corporate-Security-Services.jpg"
                alt="Security Control and Monitoring"
                class="rounded-lg shadow-xl mx-auto w-full h-64 object-cover"
              />
              <div
                class="absolute -bottom-4 left-1/2 transform -translate-x-1/2 bg-green-600 text-white px-4 py-2 rounded-full text-sm font-semibold"
              >
                24/7 Monitoring & Control
              </div>
            </div>
          </div>
        </div>

        <!-- Service Quality -->
        <div class="bg-white rounded-2xl shadow-xl p-8 border-l-4 border-saffron-500">
          <div class="flex items-center mb-6">
            <div class="text-4xl mr-4">�️</div>
            <h3 class="text-2xl font-bold text-gray-900">Our Service Commitment</h3>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="text-center">
              <div class="text-3xl mb-2">�‍♂️</div>
              <h4 class="font-semibold text-gray-900 mb-2">Trained Personnel</h4>
              <p class="text-gray-600 text-sm">
                Professional security guards with proper training and certifications
              </p>
            </div>
            <div class="text-center">
              <div class="text-3xl mb-2">⏰</div>
              <h4 class="font-semibold text-gray-900 mb-2">24/7 Service</h4>
              <p class="text-gray-600 text-sm">
                Round-the-clock security coverage for your industrial facilities
              </p>
            </div>
            <div class="text-center">
              <div class="text-3xl mb-2">🏭</div>
              <h4 class="font-semibold text-gray-900 mb-2">Industrial Focus</h4>
              <p class="text-gray-600 text-sm">
                Specialized security solutions for factories and industrial complexes
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
            Why Choose Manaram Security?
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Our comprehensive security solutions combine expert manpower with cutting-edge
            technology to deliver unmatched protection and peace of mind.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path
                  fill-rule="evenodd"
                  d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">Expert Manpower</h3>
            <p class="text-gray-600">
              Professionally trained personnel with mandatory certifications and extensive
              experience in security management.
            </p>
          </div>

          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path
                  fill-rule="evenodd"
                  d="M3 4a1 1 0 011-1h12a1 1 0 011 1v2a1 1 0 01-1 1H4a1 1 0 01-1-1V4zm0 4a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H4a1 1 0 01-1-1V8zm8 0a1 1 0 011-1h4a1 1 0 011 1v2a1 1 0 01-1 1h-4a1 1 0 01-1-1V8zm0 4a1 1 0 011-1h4a1 1 0 011 1v2a1 1 0 01-1 1h-4a1 1 0 01-1-1v-2z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">Advanced Technology</h3>
            <p class="text-gray-600">
              State-of-the-art CCTV systems, biometric access controls, and alarm systems for
              comprehensive security coverage.
            </p>
          </div>

          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path
                  fill-rule="evenodd"
                  d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">24/7 Monitoring</h3>
            <p class="text-gray-600">
              Round-the-clock vigilance and rapid response capabilities to ensure continuous
              protection and immediate action.
            </p>
          </div>

          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path
                  fill-rule="evenodd"
                  d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">Customized Solutions</h3>
            <p class="text-gray-600">
              Tailored security services designed specifically for corporates, residential
              complexes, and industrial sectors.
            </p>
          </div>

          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path
                  fill-rule="evenodd"
                  d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">ISO Certified</h3>
            <p class="text-gray-600">
              ISO 9001:2015 certified for security and allied services, ensuring quality and
              compliance with international standards.
            </p>
          </div>

          <div
            class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300"
          >
            <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewBox="0 0 20 20">
                <path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-4">Trusted by Leaders</h3>
            <p class="text-gray-600">
              Strong reputation and trusted by leading businesses across various sectors including
              malls, offices, and residential complexes.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-blue-900 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
          <div class="text-center">
            <div class="text-4xl md:text-5xl font-bold mb-2">24/7</div>
            <div class="text-lg text-blue-200">Monitoring</div>
          </div>
          <div class="text-center">
            <div class="text-4xl md:text-5xl font-bold mb-2">100+</div>
            <div class="text-lg text-blue-200">Trained Personnel</div>
          </div>
          <div class="text-center">
            <div class="text-4xl md:text-5xl font-bold mb-2">50+</div>
            <div class="text-lg text-blue-200">Satisfied Clients</div>
          </div>
          <div class="text-center">
            <div class="text-4xl md:text-5xl font-bold mb-2">5+</div>
            <div class="text-lg text-blue-200">Years Experience</div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">
          Ready to Secure Your Business?
        </h2>
        <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto">
          Get in touch with our security experts today for a free consultation and customized
          security solution tailored to your specific needs.
        </p>
        <RouterLink
          to="/contact"
          class="inline-block bg-blue-600 hover:bg-blue-700 text-white px-8 py-4 rounded-lg text-lg font-semibold transition-all duration-300 transform hover:scale-105"
        >
          Contact Us Today
        </RouterLink>
      </div>
    </section>
  </div>
</template>

<script setup>
// Component logic can be added here if needed
</script>
