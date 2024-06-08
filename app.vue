<script setup>
useSeoMeta({
  ogImage: ' ',
  twitterCard: 'summary_large_image',
  twitterTitle: 'OO',
  twitterDescription:
    'WebRTC-powered Peer-to-Peer webcam surveillance application for real-time monitoring platform.',
  twitterImage: ' ',
  twitterSite: ' ',
  twitterCreator: ' '
})
</script>

<template>
  <NuxtPwaManifest />
  <div class="relative min-h-[100vh]">
    <NavBar />

    <NuxtPage />
  </div>
</template>
