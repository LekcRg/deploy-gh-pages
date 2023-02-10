<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="hello-world">
    <h1 class="title">{{ msg }}</h1>
  </div>
</template>

<style scoped lang="scss">
  .title {
    font-size: 64px;
    font-weight: normal;
  }
</style>
