<script setup lang="ts">
import { ElConfigProvider } from 'element-plus'
</script>

<template>
  <ElConfigProvider>
    <!-- <RouterLink to="/about">About</RouterLink> -->
    <RouterView />
  </ElConfigProvider>
</template>
