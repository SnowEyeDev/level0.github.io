<template>
    <NuxtLink :to="itemLink" class="font-mono hover:text-black">// {{ itemText }}</NuxtLink>
</template>

<script setup lang="ts">
defineProps<{ itemNum: number, itemText: string, itemLink: string }>()
</script>

<style>

</style>