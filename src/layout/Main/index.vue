<template>
  <div class="main">
    <div class="main-top">
      <div class="breadcrumb-container">集群 > 集群节点管理 > 节点替换</div>
      <div class="info">当前集群：三千</div>
    </div>
    <el-divider />
    <div class="main-container"><RouterView /></div>
  </div>
</template>

<script setup></script>

<style scoped lang="scss">
.main {
  .main-top {
    display: flex;
    justify-content: space-between;
    height: 30px;
    padding-right: 10px;
    padding-left: 10px;
    line-height: 30px;
    font-size: 12px;
    color: #777;
  }

  .el-divider--horizontal {
    margin: 0;
  }
}
.main-container {
  padding-right: 10px;
  padding-left: 10px;
  padding-top: 10px;
}
</style>
