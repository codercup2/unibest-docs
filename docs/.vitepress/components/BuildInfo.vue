<!-- .vitepress/components/BuildInfo.vue -->
<template>
  <div class="build-info" :data-build-time="buildTime" :data-version="version">
    <p>构建时间: {{ buildTime }}</p>
    <p>版本号: {{ version }}</p>
  </div>
</template>

<script setup>
import { inject } from 'vue'

const buildTime = inject('buildTime')
const version = inject('version')
</script>

<style scoped>
.build-info {
  text-align: center;
  padding: 10px;
  background-color: #f8f8f8;
  margin-top: 20px;
}
</style>
