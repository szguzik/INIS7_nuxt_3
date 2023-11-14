<template>
  <div class="def_bg">
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
      <!-- Stopka -->
    </footer>
  </div>
</template>

<script setup>
// Tu można dodać logikę JavaScript
</script>

<style lang="scss">
/* Style CSS dla layoutu */
.def_bg {
  nav {
    background-color: black;
    width: 100%;
    color: chartreuse;
  }
}
</style>