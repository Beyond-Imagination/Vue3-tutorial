<template>
    <div>
        {{ hello }}
    </div>
</template>

<script setup lang="ts">
withDefaults(defineProps<{
    hello: string
}>(), {
    hello: 'hello world'
})
</script>

<style scoped lang="scss">
</style>
