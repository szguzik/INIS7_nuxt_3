<script setup lang="ts">
const route = useRoute();
console.log(route.params.course)
</script>

<template>
  {{ $route.params.course }}
</template>

<style scoped lang="scss">

</style>