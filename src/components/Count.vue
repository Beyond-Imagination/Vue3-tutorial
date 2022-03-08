<template>
    <div>
        {{ count }} clicked!!
    </div>
</template>

<script setup lang="ts">

defineProps<{ count: number }>()

</script>

<style scoped>
</style>