<script setup lang="ts">
import { Icon } from '@iconify/vue'

const props = defineProps<{
  title: string
  icon: string
}>()
</script>

<template>
  <div class="flex bg-zinc-800 p-2 rounded-lg">
    <Icon :icon="props.icon" class="h-5 mr-2" />
    <p class="text-sm">
      {{ props.title }}
    </p>
  </div>
</template>
