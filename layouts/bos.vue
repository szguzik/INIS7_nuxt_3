<template>
  <div class="bos_bg">
    <!-- Możesz dodać pasek nawigacji -->
    <header>
      <nav>
        <TopNav/>
      </nav>
    </header>

    <!-- Zawartość strony zostanie wstrzyknięta tutaj -->
    <main>
      <slot />
    </main>

    <!-- Możesz dodać stopkę -->
    <footer>
      <h3>to jest stopka</h3>
      <!-- Stopka -->
    </footer>
  </div>
</template>

<script setup>
// Tu można dodać logikę JavaScript
</script>

<style scoped lang="scss">
/* Style CSS dla layoutu */
.bos_bg {
  background-color: blue;

  nav {
    background-color: dodgerblue;
    width: 100%;
    color: white
  }
}
</style>