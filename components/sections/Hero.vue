<template>
  <section
    class="relative min-h-screen text-white overflow-hidden font-sans bg-cover bg-center bg-no-repeat"
    style="background-image: url(&quot;/images/hero-home-bg.png&quot;)"
  >
    <div
      class="pt-36 sm:pt-48 md:pt-60 pb-20 text-center px-4 md:px-6 relative z-10 flex flex-col items-center"
    >
      <h2
        class="text-[28px] sm:text-[36px] md:text-[52px] lg:text-[68px] font-bold leading-[1.15] sm:leading-[1.1] md:leading-[1.08] tracking-tight max-w-6xl"
      >
        The First
        <span
          class="inline-block bg-accent text-primaryDark px-2 py-1 md:px-4 md:py-1 rounded-lg mx-1 md:mx-2 transform shadow-md"
        >
          Dart-Native
        </span>
        <span>Feature Flag With DartCodeAI</span>
      </h2>

      <p
        class="mt-8 md:mt-10 max-w-xl md:max-w-3xl text-sm sm:text-base md:text-[19px] lg:text-[23px] font-medium text-white/90 leading-snug md:leading-relaxed px-4"
      >
        Feature flags built for Dart. Ship faster, roll back
        <br class="hidden md:block" />
        safely, and scale with AI-powered delivery
      </p>

      <p
        class="mt-4 text-accent font-bold text-base sm:text-lg md:text-xl lg:text-2xl"
      >
        Starting at just $1/month
      </p>

      <div
        class="mt-8 md:mt-10 flex flex-col items-center w-full max-w-md sm:max-w-none px-4"
      >
        <div
          class="flex flex-col sm:flex-row items-center justify-center gap-4 sm:gap-6 w-full"
        >
          <div class="flex flex-col w-full sm:w-auto">
            <p
              class="mb-2 text-[10px] sm:text-[11px] md:text-sm font-medium text-white/70 tracking-tight pl-1"
            >
              Valid till 15th September, 2025
            </p>
            <button
              class="w-full sm:w-[200px] md:w-[220px] bg-accent hover:brightness-110 active:scale-95 text-primaryDark font-bold py-3 rounded-xl transition-all shadow-lg text-base sm:text-lg md:text-xl"
            >
              Get Access
            </button>
          </div>

          <div class="flex flex-col w-full sm:w-auto self-end">
            <button
              class="w-full sm:w-auto border border-accent text-accent hover:bg-accent/10 active:scale-95 font-bold py-3 px-6 sm:px-8 rounded-xl transition-all text-base sm:text-lg md:text-xl"
            >
              Join AI Early Access
            </button>
          </div>
        </div>
      </div>

      <div class="mt-16 md:mt-24 w-full max-w-5xl px-4 md:px-4">
        <div
          class="p-1 md:p-2 rounded-xl md:rounded-2xl backdrop-blur-sm shadow-2xl"
        >
          <div
            class="rounded-lg md:rounded-xl overflow-hidden bg-white relative"
          >
            <div
              class="h-6 sm:h-7 md:h-9 bg-mutedBg flex items-center px-2 sm:px-3 md:px-4 gap-1 sm:gap-1.5 md:gap-2 border-b border-gray-200"
            >
              <div
                class="w-2 sm:w-2 md:w-3 h-2 sm:h-2 md:h-3 rounded-full bg-[#FF5F57]"
              ></div>
              <div
                class="w-2 sm:w-2 md:w-3 h-2 sm:h-2 md:h-3 rounded-full bg-[#FFBD2E]"
              ></div>
              <div
                class="w-2 sm:w-2 md:w-3 h-2 sm:h-2 md:h-3 rounded-full bg-[#28C840]"
              ></div>
              <div class="flex-1 flex justify-center">
                <div
                  class="bg-white px-2 py-0.5 rounded text-[8px] md:text-[10px] text-gray-400 w-2/3 sm:w-1/2 md:w-1/3 text-center border border-gray-100 truncate"
                >
                  app.dartcode.ai
                </div>
              </div>
            </div>
            <!-- Blurred background image -->
            <div class="relative w-full">
              <img
                src="/images/hero-dashboard.png"
                alt="IntelliToggle Dashboard Interface"
                class="w-full h-auto block blur-sm"
              />
              <!-- GIF overlay -->
              <div class="absolute inset-0 flex items-center justify-center">
                <img
                  src="/gifs/hero.gif"
                  alt="Interactive Dashboard Demo"
                  class="w-[90%] h-auto"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
