<template>
  <section class="py-16 sm:py-20 md:py-28 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <!-- Title -->
      <h2
        class="text-center text-[24px] sm:text-[28px] md:text-[32px] font-semibold text-primaryDark mb-12 sm:mb-14 md:mb-16"
      >
        Control & Power-focused
      </h2>

      <!-- Cards -->
      <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-8 sm:gap-10 md:gap-14">
        <!-- Card 1 -->
        <div>
          <div class="rounded-2xl bg-white">
            <img
              src="/images/connect.png"
              alt="Connect"
              class="rounded-xl w-full"
            />
          </div>

          <h4
            class="mt-4 sm:mt-6 text-base sm:text-lg font-semibold text-gray-900"
          >
            Connect
          </h4>
          <p class="mt-2 text-gray-600 text-xs sm:text-sm max-w-xs">
            Install SDK in your Dart project in 2 mins.
          </p>

          <button
            class="mt-3 sm:mt-4 inline-block border border-accent text-accent px-4 sm:px-5 py-1.5 sm:py-2 rounded-md text-xs sm:text-sm font-medium hover:bg-accent hover:text-black transition"
          >
            View Documentation
          </button>
        </div>

        <!-- Card 2 -->
        <div>
          <div class="rounded-2xl bg-white">
            <img
              src="/images/flags.png"
              alt="Create Flags"
              class="rounded-xl w-full"
            />
          </div>

          <h4
            class="mt-4 sm:mt-6 text-base sm:text-lg font-semibold text-gray-900"
          >
            Create Flags
          </h4>
          <p class="mt-2 text-gray-600 text-xs sm:text-sm max-w-xs">
            Define features in IntelliToggle dashboard.
          </p>

          <button
            class="mt-3 sm:mt-4 inline-block border border-accent text-accent px-4 sm:px-5 py-1.5 sm:py-2 rounded-md text-xs sm:text-sm font-medium hover:bg-accent hover:text-black transition"
          >
            View Documentation
          </button>
        </div>

        <!-- Card 3 -->
        <div>
          <div class="rounded-2xl bg-white">
            <img
              src="/images/ship.png"
              alt="Ship & Control"
              class="rounded-xl w-full"
            />
          </div>

          <h4
            class="mt-4 sm:mt-6 text-base sm:text-lg font-semibold text-gray-900"
          >
            Ship & Control
          </h4>
          <p class="mt-2 text-gray-600 text-xs sm:text-sm max-w-xs">
            Flip switches anytime, see instant results.
          </p>

          <button
            class="mt-3 sm:mt-4 inline-block border border-accent text-accent px-4 sm:px-5 py-1.5 sm:py-2 rounded-md text-xs sm:text-sm font-medium hover:bg-accent hover:text-black transition"
          >
            View Documentation
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
