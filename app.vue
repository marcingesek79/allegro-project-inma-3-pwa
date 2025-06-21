<template>
  <div data-atr="tenDiv">
    <NuxtRouteAnnouncer />
    <Navbar/>
    <NuxtLayout>
      <NuxtPage/>
    </NuxtLayout>
    <FooterArticles />
    <FooterMain />
  </div>
</template>
<script setup lang="ts">
useHead({
  link: [
    { rel: 'icon', type: 'image/png', href: '/favicon.png' },
    { rel: 'manifest', href: '/manifest.json' }
  ]
});
</script>