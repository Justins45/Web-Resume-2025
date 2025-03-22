<script setup lang="ts">
import Container from '@/components/Container.vue'
</script>

<template>
  <div class="bg-black min-h-screen text-white">
    <Container>
      <!-- TESTER FOR WIDTH -->
      <div class="h-2 bg-white mb-5"></div>
      <!-- header -->
      <div></div>
      <!-- about -->
      <div>
        <div>
          <h2 class="uppercase text-xs">About</h2>
          <div class="space-y-3">
            <p class="">
              An upcoming professional from Calgary Alberta. Have experience with VueJS, Tailwind,
              C#, and much more. Currently looking to supply users with services that will bow their
              socks off.
            </p>
            <p>
              Was in the workforce for 2 years, company sold, now looking to get back in with an
              improved skill set and a drive for building better apps.
            </p>
          </div>
        </div>
      </div>
      <!-- experience -->
      <div></div>
      <!-- skills  ?? cool cards? -->
      <div>
        <h2 class="uppercase text-sm">Workplace Skills</h2>
        <div class="flex flex-row flex-wrap space-x-5 mt-3">
          <p>VueJS</p>
          <p>GitHub</p>
          <p>Vitest</p>
          <p>TailwindCSS</p>
          <p>JavaScript</p>
          <p>SQL</p>
          <p>C#</p>
          <p>WordPress</p>
          <p></p>
        </div>
      </div>
      <!-- education -->
      <div></div>
    </Container>
  </div>
</template>
