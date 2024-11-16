<script setup lang="ts">
// TODO: 从远程地址获取版本号
const version = '2.5.0'
</script>

<template>
  <span
    style="
      color: green;
      font-size: 10px;
      margin-left: 4px;
      background-color: azure;
      padding: 0 4px;
      border-radius: 4px;
      display: inline-block;
      font-weight: 700;
    "
    >{{ version }}</span
  >
</template>
