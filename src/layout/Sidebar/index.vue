<template>
  <div class="sidebar">
    <div class="sidebar-logo">🤔</div>
    <div class="menu">
      <div class="menu-item">集群管理</div>
      <div class="menu-item">集群 VC 管理</div>
      <div class="menu-item">集群节点管理</div>
      <div class="menu-item">集群数据库</div>
      <div class="menu-item">资源管理</div>
      <div class="menu-item">集群参数管理</div>
      <div class="menu-item">集群监控管理</div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped lang="scss">
.sidebar {
  .sidebar-logo {
    height: 120px;
    text-align: center;
    line-height: 120px;
  }
  .menu {
    .menu-item {
      height: 40px;
      padding-left: 30px;
      font-size: 14px;
      line-height: 40px;
      color: #312f2f;

      &:hover {
        color: dodgerblue;
        background-color: white;
      }
    }
  }
}
</style>
