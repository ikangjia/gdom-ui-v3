<template>
  <div class="header">
    <div class="logo-container">Logo Xxxx 系统</div>
    <div class="top-menu-container">
      <div class="top-nav">
        <div class="top-nav-item"><span>主页</span></div>
        <div class="top-nav-item"><span>集群</span></div>
        <div class="top-nav-item"><span>主机</span></div>
        <div class="top-nav-item"><span>运维</span></div>
        <div class="top-nav-item"><span>审计</span></div>
        <div class="top-nav-item"><span>系统管理</span></div>
      </div>
      <div class="fast-menu">
        <div class="fast-menu-item">
          <el-icon><Share /></el-icon>
        </div>
        <div class="fast-menu-item">
          <el-icon><Share /></el-icon>
        </div>
        <div class="fast-menu-item">
          <el-icon><Share /></el-icon>
        </div>
        <div class="fast-menu-item">
          <el-icon><Share /></el-icon>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { Share } from '@element-plus/icons-vue'
</script>

<style scoped lang="scss">
.header {
  display: flex;
  .logo-container {
    width: 200px;
    text-align: center;
  }

  .top-menu-container {
    display: flex;
    flex: 1;
    justify-content: space-between;
    padding: 0 20px 0 10px;

    .top-nav {
      display: flex;
      .top-nav-item {
        margin-right: 20px;
        font-size: 14px;
        color: silver;

        &:hover {
          text-decoration: underline;
          color: white;
        }
      }
    }

    .fast-menu {
      display: flex;
      .fast-menu-item {
        margin-right: 15px;
      }
    }
  }
}
</style>
