<template>
  <main>
    Hello Home
    <div>
      <button @click="goToHello">
        Go to Hello
      </button>
    </div>
  </main>
</template>

<script setup lang="ts">
import { useRouter } from 'vue-router';

const router = useRouter()

function goToHello () {
  router.push('/hello/123123')
}

</script>
