<script setup lang="ts">
import { ref } from "vue";

const isOpen = ref(false);
</script>

<template>
  <header class="fixed bg-primary top-0 w-full z-50">
    <div class="max-w-7xl mx-auto px-6 py-6 flex items-center justify-between">
      <!-- Logo -->
      <img src="/svgs/intellitoggle.svg" alt="IntelliToggle" class="h-12" />

      <!-- Desktop Navigation -->
      <nav class="hidden md:flex gap-12 text-base font-medium cursor-pointer">
        <!-- Active -->
        <a class="text-white"> Home </a>

        <!-- Inactive -->
        <a class="text-white/70 hover:text-white transition"> About </a>
        <a class="text-white/70 hover:text-white transition"> Pricing </a>
      </nav>

      <!-- Desktop CTA -->
      <button
        class="hidden md:inline-flex bg-accent text-primaryDark px-7 py-3 rounded-md text-[20px] font-semibold hover:brightness-110 transition"
      >
        Start Sandbox
      </button>

      <!-- Mobile Menu Button -->
      <button
        class="md:hidden text-white"
        @click="isOpen = !isOpen"
        :aria-expanded="isOpen"
        aria-label="Toggle menu"
        aria-controls="mobile-menu"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-7 w-7"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          aria-hidden="true"
        >
          <path
            v-if="!isOpen"
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

    <!-- Mobile Menu (Animated) -->
    <transition
      enter-active-class="transition duration-300 ease-out"
      enter-from-class="opacity-0 -translate-y-4"
      enter-to-class="opacity-100 translate-y-0"
      leave-active-class="transition duration-200 ease-in"
      leave-from-class="opacity-100 translate-y-0"
      leave-to-class="opacity-0 -translate-y-4"
    >
      <nav
        v-if="isOpen"
        id="mobile-menu"
        class="md:hidden bg-primaryDark text-white px-6 py-6 space-y-5"
      >
        <!-- Active -->
        <a class="block font-medium text-lg text-white"> Home </a>

        <!-- Inactive -->
        <a class="block text-lg text-white/70"> About </a>
        <a class="block text-lg text-white/70"> Pricing </a>

        <button
          class="mt-6 w-full bg-accent text-black py-3 rounded-md text-base font-semibold hover:brightness-110 transition"
        >
          Start Sandbox
        </button>
      </nav>
    </transition>
  </header>
</template>
