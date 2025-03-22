<script setup lang="ts">
import type { Component } from 'vue'

const props = defineProps<{
  title: string
  icon: Component
}>()
</script>

<template>
  <div class="flex">
    <component :is="props.icon" class="h-16 w-16 mr-3" />
    <p class="text-sm">
      {{ props.title }}
    </p>
  </div>
</template>
