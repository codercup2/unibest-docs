<!-- .vitepress/layouts/Default.vue -->
<template>
  <div class="custom-layout">
    <VPLayout>
      <template #layout-bottom>
        <footer class="footer">
          <p>© 2024 菲哥科技公司</p>
          <p><a href="http://www.miitbeian.gov.cn/" target="_blank">粤ICP备2024160998号</a></p>
        </footer>
      </template>
    </VPLayout>
  </div>
</template>

<script setup>
import VPLayout from '@theme-default/Layout.vue'
</script>

<style scoped>
.footer {
  text-align: center;
  padding: 20px;
  background-color: #f8f8f8;
}
</style>
