<template>
  <el-container>
    <el-header height="40px;">
      <my-header />
    </el-header>
    <el-main>Main<nuxt /></el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
import MyHeader from '@/components/public/header/index.vue'
export default {
  components: {
    MyHeader
  }
}
</script>

<style lang="scss">
  @import "@/assets/css/main.css"
</style>
