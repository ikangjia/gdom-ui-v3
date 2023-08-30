<template>
  <el-config-provider :size="elConfig.size" :z-index="elConfig.zIndex">
    <RouterView />
  </el-config-provider>
</template>
<script setup>
import {reactive} from "vue";
import { RouterView } from 'vue-router'

const elConfig = reactive({
  zIndex: 3000,
  size: 'small', // small、large、default
})
</script>

<style scoped lang="scss">
</style>
