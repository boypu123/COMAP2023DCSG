<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Introduction from '@/components/HelloWorld.vue';
import Headers from './components/Headers.vue';
import Information from '@/components/Information.vue';

</script>

<template>
  <Headers/>
  <Introduction/>
  <Information/>
</template>

<style scoped>
</style>
