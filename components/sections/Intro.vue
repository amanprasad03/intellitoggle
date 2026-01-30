<template>
  <section class="py-16 sm:py-20 md:py-28 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <!-- Section Title -->
      <h2
        class="text-center text-[24px] sm:text-[28px] md:text-[32px] font-semibold text-primaryDark mb-12 sm:mb-14 md:mb-16"
      >
        What Is IntelliToggle
      </h2>

      <!-- Content -->
      <div class="grid md:grid-cols-2 gap-10 sm:gap-12 md:gap-16 items-center">
        <!-- LEFT: Text -->
        <div class="px-4 sm:px-0">
          <h3
            class="text-[22px] sm:text-[26px] md:text-[30px] font-semibold text-gray-900 leading-snug"
          >
            Your AI Dart App's Control Panel For
            <br />
            Feature Releases
          </h3>

          <p
            class="mt-4 sm:mt-5 text-sm sm:text-base text-gray-600 leading-relaxed max-w-lg"
          >
            IntelliToggle is a "Dart-Powered" feature flag that lets you turn
            features on/off instantly in your application without redeploying
            code. It allows you control roll-outs, run experiments, and fix bugs
            faster.
          </p>

          <div class="mt-5 sm:mt-6">
            <p class="font-semibold text-gray-900 mb-2">Benefits</p>
            <ul
              class="space-y-2 text-sm sm:text-base text-gray-600 list-disc ml-5"
            >
              <li>Toggle new features without app updates</li>
              <li>Roll out to specific users or regions</li>
              <li>Instantly rollback when needed</li>
            </ul>
          </div>
        </div>

        <!-- RIGHT: Dashboard Image -->
        <div class="relative px-4 sm:px-0">
          <div
            class="rounded-2xl bg-gradient-to-br from-primary to-primaryDark p-[28px] sm:p-[28px]"
          >
            <img
              src="/images/intro.png"
              alt="IntelliToggle Dashboard"
              class="rounded-xl bg-white shadow-2xl"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
