<template>
  <header>
    <span>Issue Generator</span>
    <span>English</span>
  </header>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
header {
  background: #108ee9;
  height: 50px;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-sizing: border-box;
  padding: 0 20px;
  color: #fff;
}
</style>
