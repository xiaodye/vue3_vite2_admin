<template>
  <div class="home">
    <el-button disabled>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </div>
</template>

<script setup>
import { ref, reactive } from "vue"
console.log("nice")
</script>

<style lang="scss" scoped>
.home {
  min-height: 100vh;
  background-color: #fff;
}
</style>
