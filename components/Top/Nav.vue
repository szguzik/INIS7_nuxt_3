<script setup lang="ts">

</script>

<template>
  <nav class="navbar is-link is-block" role="navigation" aria-label="main navigation">
    <div class="container pt-2">
      <input class="input is-normal" type="text" placeholder="Wyszukaj ...">
      <div class="navbar-start">
        <a class="navbar-item">
          <span class="material-symbols-outlined pr-1">favorite</span>Schowek
        </a>
        <a class="navbar-item">
          <span class="material-symbols-outlined pr-1">person_add</span>
          Rejestracja
        </a>
        <a class="navbar-item">
          <span class="material-symbols-outlined pr-1">person</span>
          Logowanie
        </a>
      </div>
    </div>
    <div class="container">
      <div class="navbar-brand">
        <NuxtLink class="navbar-item" to="/">
          <img src="/logo/logo.png" style="width: 100%">
        </NuxtLink>

        <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item">
            <span class="material-symbols-outlined p-1">mail</span>
            Wiadomości
          </a>

          <a class="navbar-item">
            <span class="material-symbols-outlined p-1">info</span>
            Komunikaty
          </a>

          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link">
              <span class="material-symbols-outlined p-1">school</span>
              Przedmioty
            </a>

            <div class="navbar-dropdown">
              <a class="navbar-item">
                Zaawansowane projektowanie aplikacji mobilnych
              </a>
              <a class="navbar-item">
                Programowanie rozproszone
              </a>
              <a class="navbar-item">
                Pracownia projektowa
              </a>
              <a class="navbar-item">
                Pracownia projektowa 2
              </a>
              <a class="navbar-item">
                Język Python - frameworki
              </a>
              <a class="navbar-item">
                Wprowadzenie do tworzenia gier
              </a>
              <a class="navbar-item">
                Konsola, podstawy linuxa i git
              </a>
              <a class="navbar-item">
                IDE i narzędzia deweloperskie chrome
              </a>
              <a class="navbar-item">
                Podstawy programowania
              </a>
              <a class="navbar-item">
                Inżynieria systemów i analiza systemowa
              </a>
              <a class="navbar-item">
                Projektowanie witryn typu SPA
              </a>
              <hr class="navbar-divider">
              <a class="navbar-item">
                Kursy dodatkowe
              </a>
            </div>
          </div>
        </div>

        <div class="navbar-end">
          <a class="navbar-item">
            <span class="material-symbols-outlined p-1">contact_page</span>
            <strong>Kontakt</strong>
          </a>
        </div>
      </div>
    </div>

  </nav>

</template>

<style scoped lang="scss">
nav {
  min-height: 60px;
}

</style>