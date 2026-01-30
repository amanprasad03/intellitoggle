<template>
  <section class="bg-mutedBg py-16 sm:py-20 md:py-28">
    <div
      class="max-w-7xl mx-auto px-4 sm:px-6 grid md:grid-cols-2 gap-10 sm:gap-16 md:gap-20 items-center"
    >
      <!-- Logo Card -->
      <div
        class="bg-white rounded-2xl border border-primary/30 h-[320px] sm:h-[400px] md:h-[460px] flex items-center justify-center"
      >
        <img
          src="/images/open-feature.png"
          alt="OpenFeature"
          class="max-w-[220px] sm:max-w-[260px] md:max-w-[320px]"
        />
      </div>

      <!-- Content -->
      <div class="max-w-xl px-4 sm:px-0">
        <h3
          class="text-xl sm:text-2xl md:text-3xl font-semibold text-primaryDark mb-4 sm:mb-5"
        >
          Seamless Feature Management with OpenFeature
        </h3>

        <p
          class="text-sm sm:text-base text-gray-500 leading-relaxed mb-6 sm:mb-8"
        >
          Aortem now integrates with OpenFeature to provide developers with a
          powerful, standardized approach to feature flagging and dynamic
          configuration. Ship features faster, test safely, and optimize user
          experiences effortlessly.
        </p>

        <button
          class="inline-flex items-center gap-2 bg-accent text-primaryDark px-5 sm:px-6 py-2.5 sm:py-3 rounded-md font-semibold text-sm sm:text-base hover:brightness-105 transition"
        >
          Learn More
          <span class="text-lg">→</span>
        </button>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
