<template>
  <div>
    <Header class="header" />
    <div class="middle-container">
      <SideBar class="sidebar" />
      <Main class="main" />
    </div>
    <Footer class="footer" />
  </div>
</template>
<script setup>
import Header from './Header/index.vue'
import SideBar from './Sidebar/index.vue'
import Main from './Main/index.vue'
import Footer from './Footer/index.vue'
</script>

<style scoped lang="scss">
.header {
  height: 40px;
  background-color: #222;
  color: white;
  line-height: 40px;
}
.middle-container {
  height: calc(100vh - 40px - 20px);
  display: flex;

  .sidebar {
    width: 200px;
    background-color: #f7f8f8;
  }

  .main {
    flex: 1;
  }
}
.footer {
  height: 20px;
  background-color: #222;
  color: white;
}
</style>
