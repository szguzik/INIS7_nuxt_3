<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup>
const data = ref("")

onBeforeMount(() => {
  localStorage.setItem("test3", "test")
})

onMounted(() => {
  data.value = localStorage.getItem("test3")
})
</script>