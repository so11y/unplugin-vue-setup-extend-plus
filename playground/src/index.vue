<script setup lang="ts" inheritAttrs="false" name="Count" >
import { ref } from 'vue'
const num = ref(0)
</script>

<template>
  <div>
    count: {{ num }} <button @click="num++">
      add
    </button>
  </div>
</template>
