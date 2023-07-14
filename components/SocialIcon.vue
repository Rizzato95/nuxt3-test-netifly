<template>
    <NuxtLink :to="url" target="__blank" class="text-white ">
      <img :src="iconPath" :alt="name" class="w-7 fill-white brightness-0 invert opacity-40 hover:opacity-100 hover:scale-110 transition-all"/>
    </NuxtLink>
</template>

<script setup lang="ts">
    const props = defineProps({
        name: String,
        iconPath: String,
        url: String
    });

</script>