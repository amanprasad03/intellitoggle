<template>
  <footer class="bg-mutedBg pt-16 sm:pt-20 pb-10 sm:pb-12">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <!-- Main Footer Content - All in one row on desktop -->
      <div
        class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-10 sm:gap-12 lg:gap-8"
      >
        <!-- Brand Section -->
        <div>
          <!-- Logo -->
          <img
            src="/svgs/footer-intellitoggle-logo.svg"
            alt="IntelliToggle"
            class="h-10 sm:h-12 mb-5 sm:mb-6"
          />

          <!-- Description -->
          <p class="text-sm sm:text-base text-gray-600 mb-6 sm:mb-8">
            IntelliToggle is built by AORTEM, a company focused on powering
            scalable, multi-platform developer tools.
          </p>

          <!-- GitHub Icon -->
          <a
            href="#"
            target="_blank"
            rel="noopener noreferrer"
            class="inline-block"
          >
            <img
              src="/images/footer-github.png"
              alt="GitHub"
              class="w-5 h-5 sm:w-6 sm:h-6"
            />
          </a>
        </div>

        <!-- Resources -->
        <div>
          <h4
            class="text-tableHeader font-semibold text-base sm:text-lg mb-4 sm:mb-5"
          >
            Resources
          </h4>
          <ul class="space-y-3 text-sm sm:text-base text-gray-600">
            <li>
              <a href="#" class="hover:text-primary transition"
                >Why IntelliToggle Is Different</a
              >
            </li>
            <li>
              <a href="#" class="hover:text-primary transition"
                >Customer Support</a
              >
            </li>
            <li>
              <a href="#" class="hover:text-primary transition"
                >Terms & Conditions</a
              >
            </li>
            <li>
              <a href="#" class="hover:text-primary transition"
                >Privacy Policy</a
              >
            </li>
          </ul>
        </div>

        <!-- Company -->
        <div>
          <h4
            class="text-tableHeader font-semibold text-base sm:text-lg mb-4 sm:mb-5"
          >
            Company
          </h4>
          <ul class="space-y-3 text-sm sm:text-base text-gray-600">
            <li>
              <a href="#" class="hover:text-primary transition">Pricing</a>
            </li>
            <li>
              <a href="#" class="hover:text-primary transition"
                >Documentation</a
              >
            </li>
            <li>
              <a href="#" class="hover:text-primary transition">About Us</a>
            </li>
          </ul>
        </div>

        <!-- Newsletter -->
        <div>
          <h4
            class="text-tableHeader font-semibold text-base sm:text-lg mb-4 sm:mb-5"
          >
            Subscribe to Newsletter
          </h4>

          <div class="flex flex-col gap-2">
            <input
              type="email"
              placeholder="Enter email address"
              class="w-full px-4 sm:px-5 py-3 rounded-lg border border-gray-300 focus:outline-none focus:border-primary text-sm sm:text-base"
            />
            <button
              class="w-full bg-accent text-primaryDark font-bold px-6 py-3 rounded-lg hover:brightness-110 transition text-sm sm:text-base"
            >
              Subscribe
            </button>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts"></script>
