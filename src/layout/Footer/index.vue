<template>
  <div class="footer">
    <div>
      中文（简体）<el-icon><CaretBottom /></el-icon>
    </div>
    <div>
      <span>@copyright 2022-2023 xxx 版权所有</span>
      <el-divider direction="vertical" />
      <span>{{ new Date() }}</span>
    </div>
  </div>
</template>

<script setup>
import { CaretBottom } from '@element-plus/icons-vue'
</script>

<style scoped>
.footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;

  font-size: 12px;
}
</style>
