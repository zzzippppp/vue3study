<script setup lang="ts">
  import {ref} from "vue";

  const name = ref("默认值")


</script>

<template>
  <input v-model="name" placeholder="请输入你的名字"/>
  <p>{{name}}</p>>
</template>

<style scoped>

</style>