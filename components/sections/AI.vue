<template>
  <section
    class="relative py-16 sm:py-20 md:py-28 text-white overflow-hidden"
    style="background: linear-gradient(135deg, #42389e 0%, #1a1c3d 100%)"
  >
    <!-- Background circuit image -->
    <div
      class="absolute inset-0 bg-cover bg-center opacity-40"
      style="background-image: url(&quot;/images/ai-image.png&quot;)"
    ></div>

    <!-- Content -->
    <div class="relative max-w-7xl mx-auto px-4 sm:px-6">
      <!-- Badge -->
      <div class="flex justify-center mb-5 sm:mb-6">
        <span
          class="inline-block bg-accent text-primaryDark font-bold px-4 sm:px-5 py-1.5 sm:py-2 rounded-full text-xs sm:text-sm"
        >
          Coming Soon
        </span>
      </div>

      <!-- Title -->
      <h2
        class="text-center text-[24px] sm:text-[28px] md:text-[32px] font-semibold mb-10 sm:mb-12 md:mb-14"
      >
        DartCodeAI That Actually Changes Flagging
      </h2>

      <!-- Feature Cards -->
      <div
        class="grid sm:grid-cols-2 gap-8 sm:gap-10 md:gap-12 max-w-6xl mx-auto"
      >
        <!-- Card 1: AutoFlag AI -->
        <div
          class="bg-white/5 backdrop-blur-sm rounded-2xl px-8 sm:px-10 py-8 sm:py-10 border border-white/20 hover:bg-white/10 transition"
        >
          <div class="flex items-start gap-5">
            <div
              class="flex-shrink-0 bg-white rounded-xl w-14 h-14 flex items-center justify-center"
            >
              <!-- Flag icon placeholder -->
              <svg
                class="w-7 h-7 text-primary"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path d="M14.4 6L14 4H5v17h2v-7h5.6l.4 2h7V6z" />
              </svg>
            </div>
            <div>
              <h4 class="font-semibold text-lg sm:text-xl mb-3">
                AutoFlag AI (LLM-Assisted Flag Creation)
              </h4>
              <p class="text-sm sm:text-base text-white/80 leading-relaxed">
                Create new flags just by typing what you need. The AI names it,
                sets rules, and configures targeting for you.
              </p>
            </div>
          </div>
        </div>

        <!-- Card 2: SmartRamp AI -->
        <div
          class="bg-white/5 backdrop-blur-sm rounded-2xl px-8 sm:px-10 py-8 sm:py-10 border border-white/20 hover:bg-white/10 transition"
        >
          <div class="flex items-start gap-5">
            <div
              class="flex-shrink-0 bg-white rounded-xl w-14 h-14 flex items-center justify-center"
            >
              <!-- Chart icon placeholder -->
              <svg
                class="w-7 h-7 text-primary"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M3 13h2v8H3v-8zm4-6h2v14H7V7zm4-4h2v18h-2V3zm4 9h2v9h-2v-9zm4-3h2v12h-2V9z"
                />
              </svg>
            </div>
            <div>
              <h4 class="font-semibold text-lg sm:text-xl mb-3">
                SmartRamp AI (AI-Driven Rollout Optimization)
              </h4>
              <p class="text-sm sm:text-base text-white/80 leading-relaxed">
                Rollouts that adjust themselves. AI expands, pauses, or rolls
                back based on real-time metrics.
              </p>
            </div>
          </div>
        </div>

        <!-- Card 3: ExplainFlags AI -->
        <div
          class="bg-white/5 backdrop-blur-sm rounded-2xl px-8 sm:px-10 py-8 sm:py-10 border border-white/20 hover:bg-white/10 transition"
        >
          <div class="flex items-start gap-5">
            <div
              class="flex-shrink-0 bg-white rounded-xl w-14 h-14 flex items-center justify-center"
            >
              <!-- Search icon placeholder -->
              <svg
                class="w-7 h-7 text-primary"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"
                />
              </svg>
            </div>
            <div>
              <h4 class="font-semibold text-lg sm:text-xl mb-3">
                ExplainFlags AI (LLM Root-Cause + Insights)
              </h4>
              <p class="text-sm sm:text-base text-white/80 leading-relaxed">
                Understand issues instantly with AI-generated, plain-language
                insights tied to your flags.
              </p>
            </div>
          </div>
        </div>

        <!-- Card 4: AutoSegment AI -->
        <div
          class="bg-white/5 backdrop-blur-sm rounded-2xl px-8 sm:px-10 py-8 sm:py-10 border border-white/20 hover:bg-white/10 transition"
        >
          <div class="flex items-start gap-5">
            <div
              class="flex-shrink-0 bg-white rounded-xl w-14 h-14 flex items-center justify-center"
            >
              <!-- Target icon placeholder -->
              <svg
                class="w-7 h-7 text-primary"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm0-14c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6zm0 10c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4z"
                />
              </svg>
            </div>
            <div>
              <h4 class="font-semibold text-lg sm:text-xl mb-3">
                AutoSegment AI (Behavioral Segmentation)
              </h4>
              <p class="text-sm sm:text-base text-white/80 leading-relaxed">
                Target the right users automatically. AI builds segments from
                live behavior—no manual rules.
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Enterprise Only -->
      <p
        class="text-center text-accent font-semibold mt-8 sm:mt-10 text-base sm:text-lg md:text-xl"
      >
        Enterprise Only
      </p>

      <!-- Bottom CTA -->
      <div
        class="mt-8 sm:mt-10 max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-6 sm:gap-8 px-8 sm:px-10 md:px-12 py-8 sm:py-10 rounded-2xl bg-white/5 backdrop-blur-md border border-white/10"
      >
        <div class="text-center md:text-left">
          <p class="font-semibold text-lg sm:text-xl mb-2">
            <span class="text-accent">Be The First</span> To Try Out Our New AI
            Features.
          </p>
        </div>

        <div
          class="flex flex-col sm:flex-row items-center gap-3 sm:gap-4 w-full md:w-auto"
        >
          <input
            type="email"
            placeholder="Enter email address"
            class="w-full sm:w-72 px-5 py-3 rounded-lg bg-white/10 border border-white/20 text-white placeholder-white/50 focus:outline-none focus:border-accent text-sm"
          />
          <button
            class="w-full sm:w-auto whitespace-nowrap px-6 sm:px-7 py-3 bg-accent text-primaryDark font-bold rounded-lg hover:brightness-110 transition text-sm"
          >
            Join AI Early Access
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>
