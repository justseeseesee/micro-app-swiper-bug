<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
 <div>
  <!-- <iframe src="http://localhost:4000" frameborder="0"></iframe> -->
   <micro-app name="my-app" url="http://localhost:4000" iframe></micro-app>
 </div>
 
</template>

<style >
.read-the-docs {
  color: #888;
}
</style>
