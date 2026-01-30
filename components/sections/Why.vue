<template>
  <section class="py-16 sm:py-20 md:py-28 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 text-center">
      <!-- Heading -->
      <h2
        class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-semibold text-primaryDark mb-12 sm:mb-16 md:mb-20"
      >
        Why Teams Use IntelliToggle
      </h2>

      <!-- Feature Cards -->
      <div
        class="grid sm:grid-cols-2 md:grid-cols-3 gap-12 sm:gap-16 md:gap-20 mb-12 sm:mb-14 md:mb-16"
      >
        <!-- Card 1: Safer, faster rollouts -->
        <div class="text-left">
          <img
            src="/images/why-rollout.png"
            alt="Rollout icon"
            width="126"
            height="126"
            class="mb-5 sm:mb-6"
          />

          <h4
            class="text-base sm:text-lg md:text-xl font-semibold text-primaryDark mb-2"
          >
            Safer, faster rollouts
          </h4>

          <p class="text-gray-500 text-sm sm:text-base leading-relaxed">
            Control feature releases in minutes, not weeks without risking
            production stability.
          </p>
        </div>

        <!-- Card 2: Confidence to ship -->
        <div class="text-left">
          <img
            src="/images/why-ship.png"
            alt="Ship icon"
            width="126"
            height="126"
            class="mb-5 sm:mb-6"
          />

          <h4
            class="text-base sm:text-lg md:text-xl font-semibold text-primaryDark mb-2"
          >
            Confidence to ship
          </h4>

          <p class="text-gray-500 text-sm sm:text-base leading-relaxed">
            "Flip, target, and roll back. Engineers ship more often knowing they
            can undo mistakes."
          </p>
        </div>

        <!-- Card 3: Future-ready with AI delivery -->
        <div class="text-left">
          <img
            src="/images/why-ai.png"
            alt="AI icon"
            width="126"
            height="126"
            class="mb-5 sm:mb-6"
          />

          <h4
            class="text-base sm:text-lg md:text-xl font-semibold text-primaryDark mb-2"
          >
            Future-ready with AI delivery
          </h4>

          <p class="text-gray-500 text-sm sm:text-base leading-relaxed">
            Built for Dart workflows and already prepared for AI-powered rollout
            automation tomorrow.
          </p>
        </div>
      </div>

      <!-- Case Study CTA -->
      <div
        class="mx-auto bg-mutedBg border border-primary/30 rounded-xl px-5 sm:px-6 md:px-8 py-4 sm:py-5 flex flex-col md:flex-row items-center justify-between gap-4 sm:gap-5 md:gap-6"
      >
        <p
          class="text-primaryDark font-medium text-center md:text-left text-sm sm:text-base md:text-lg"
        >
          <span class="font-semibold"> Read a 2-min case note: </span>
          <span class="text-gray-600">
            How a sample Flutter app shipped faster with IntelliToggle
          </span>
        </p>

        <button
          class="bg-accent text-primaryDark px-5 sm:px-6 py-2.5 sm:py-3 rounded-md font-semibold text-sm sm:text-base md:text-lg hover:brightness-105 transition whitespace-nowrap"
        >
          Read Now
        </button>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
