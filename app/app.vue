<template>
  <div>
    <NuxtLoadingIndicator/>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
import { useSeoMeta } from 'nuxt/app'

useSeoMeta({
  title: 'Dantès',
  description: 'Não seguimos tendências — criamos identidade.',
  ogImage: 'https://example.com/image.png',
})
</script>