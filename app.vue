<template>
  <NuxtPage />
</template>

<script setup>
const title = ref('Marco Rizzato')
const description = ref('A passionate full stack developer')

useHead({
  title,
  htmlAttrs: {
    lang: 'en'
  },
  meta: [{
    name: 'description',
    content: description,
    charset: 'utf-8'
  }],
  link: [
    { rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }
  ]
})
</script>
