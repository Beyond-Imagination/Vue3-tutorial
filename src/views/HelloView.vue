<template>
    <div>
        Hello View {{ params.articleId }}
    </div>
</template>

<script lang="ts" setup>
import { onMounted } from 'vue';
import { useRoute } from 'vue-router'

const route = useRoute() 

const params = route.params

onMounted(() => {
    console.log(params)
})
</script>

<style scoped lang="scss">
</style>
