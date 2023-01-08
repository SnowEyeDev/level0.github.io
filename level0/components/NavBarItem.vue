<template>
    <div class="font-mono">
        <div class="text-[9px] text-right">nav[{{ itemNum }}]</div>
        <div class="cursor-pointer">// {{ itemText }}</div>
    </div>
</template>

<script setup lang="ts">
defineProps<{ itemNum: number, itemText: string }>()
</script>