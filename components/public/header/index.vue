<template>
  <div class="m-header">
    <el-row>
      <top-bar />
    </el-row>
  </div>
</template>
<script>
import topBar from './topbar.vue'
export default {
  components: {
    topBar
  }
}
</script>
<style lang="scss">
  @import "@/assets/css/public/layout.scss"
</style>
