<template>
  <section class="bg-mutedBg py-16 sm:py-20 md:py-28">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 text-center">
      <!-- Heading -->
      <h2
        class="text-2xl sm:text-3xl md:text-4xl font-semibold text-primaryDark mb-10 sm:mb-12"
      >
        Plans Built For Every Stage Of Growth
      </h2>

      <!-- Price Card -->
      <div class="flex flex-col items-center mb-10 sm:mb-12 md:mb-14">
        <div
          class="text-white rounded-2xl px-10 sm:px-12 md:px-16 py-8 sm:py-10 md:py-12 shadow-lg mb-4 sm:mb-5"
          style="background: linear-gradient(135deg, #42389e 0%, #1a1c3d 100%)"
        >
          <p class="text-xs sm:text-sm mb-2 sm:mb-3 text-white/80">
            Prices starts at
          </p>
          <div class="flex items-baseline justify-center gap-1">
            <span class="text-4xl sm:text-5xl md:text-6xl font-bold">$10</span>
            <span class="text-base sm:text-lg md:text-xl text-white/80"
              >/month</span
            >
          </div>
        </div>

        <button
          class="bg-accent text-primaryDark font-bold px-8 sm:px-10 py-3 sm:py-3.5 rounded-xl hover:brightness-110 transition text-sm sm:text-base"
        >
          View Subscription Details
        </button>
      </div>

      <!-- Free Sandbox CTA -->
      <div
        class="bg-white rounded-xl border border-black/10 px-6 sm:px-8 md:px-10 py-6 sm:py-8 flex flex-col md:flex-row items-center justify-between gap-5 sm:gap-6"
      >
        <div class="text-center md:text-left">
          <h3 class="text-lg sm:text-xl font-semibold text-primaryDark mb-2">
            Start Your 7-Day Free Sandbox Plan
          </h3>
          <p class="text-xs sm:text-sm text-gray-500">
            Join over 1000+ startups already growing with Untitled.
          </p>
        </div>

        <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 w-full md:w-auto">
          <button
            class="bg-accent text-primaryDark font-bold px-6 sm:px-7 py-2.5 sm:py-3 rounded-lg hover:brightness-110 transition text-sm whitespace-nowrap"
          >
            Get Started
          </button>
          <button
            class="border-2 border-accent text-accent font-bold px-6 sm:px-7 py-2.5 sm:py-3 rounded-lg hover:bg-accent/10 transition text-sm whitespace-nowrap"
          >
            Learn More
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
