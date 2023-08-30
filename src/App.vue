<template>
  <el-config-provider :size="elConfig.size" :z-index="elConfig.zIndex">
    <RouterView />
  </el-config-provider>
</template>
<script setup>
const elConfig = reactive({
  zIndex: 3000,
  size: 'small' // small、large、default
})
</script>

<style scoped lang="scss"></style>
