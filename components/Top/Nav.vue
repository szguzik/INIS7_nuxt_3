<script setup lang="ts">

</script>

<template>
  <div class="nav">
      <ul class="items">
        <li>Home</li>
        <li>Studenci</li>
        <li>Kontakt</li>
      </ul>
  </div>

</template>

<style scoped lang="scss">
.nav {
  display: flex;
  .items {
    width: 90%;
    margin: 0 auto;
    display: inherit;
    list-style-type: none;
    justify-content: center;
    li {
      padding: 0 5px;
      text-decoration: none;
    }
  }
}
</style>