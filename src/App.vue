<script setup lang="ts">
import { useRouter } from 'vue-router'

const router = useRouter()
const goToList = () => {
  router.push('/list')
}
</script>

<template>
  <div>我是App</div>
  <el-button @click="$router.push('/home')">主页</el-button>
  <el-button @click="goToList">列表</el-button>
</template>

<style scoped></style>
