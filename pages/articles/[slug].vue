<script setup lang="ts">
const route = useRoute();
console.log(route.params.slug)
</script>

<template>
{{ $route.params.slug }}
</template>

<style scoped>

</style>