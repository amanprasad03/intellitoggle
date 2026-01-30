<template>
  <section class="py-16 sm:py-20 md:py-28 px-4 sm:px-6">
    <div
      class="relative max-w-6xl mx-auto rounded-3xl overflow-hidden shadow-2xl"
      style="
        background: linear-gradient(135deg, #42389e 0%, #0f1026 100%);
        box-shadow:
          0 20px 60px rgba(0, 0, 0, 0.3),
          0 10px 30px rgba(66, 56, 158, 0.2);
      "
    >
      <!-- Dark overlay for better text readability -->
      <div
        class="absolute inset-0 bg-gradient-to-b from-transparent via-primaryDark/20 to-primaryDark/40"
      ></div>

      <!-- Content -->
      <div
        class="relative px-6 sm:px-10 md:px-16 lg:px-20 py-16 sm:py-20 md:py-24 text-white"
      >
        <h2
          class="text-xl text-center sm:text-3xl md:text-4xl lg:text-5xl font-bold leading-tight mb-4 sm:mb-5"
        >
          Launch Features Confidently With AI<br class="hidden sm:block" />
          Driven Feature Flags
        </h2>

        <p
          class="text-base text-center sm:text-lg md:text-xl text-white/90 mb-10 sm:mb-12 md:mb-14 font-medium"
        >
          Start for free, scale as your team grows
        </p>

        <div
          class="flex flex-col sm:flex-row justify-center items-center gap-4 sm:gap-5 md:gap-6"
        >
          <!-- Primary CTA Button -->
          <button
            class="w-full text-primary sm:w-auto px-8 sm:px-10 md:px-12 py-3.5 sm:py-4 md:py-4.5 bg-accent text-primaryDark font-bold text-base sm:text-lg rounded-xl hover:brightness-110 active:scale-95 transition-all shadow-lg hover:shadow-xl"
          >
            Start for $1/mo
          </button>

          <!-- Secondary CTA Button -->
          <button
            class="w-full sm:w-auto px-8 sm:px-10 md:px-12 py-3.5 sm:py-4 md:py-4.5 border-2 border-accent text-accent font-bold text-base sm:text-lg rounded-xl hover:bg-accent hover:text-primary active:scale-95 transition-all"
          >
            Join AI Early Access
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
