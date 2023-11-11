<script setup>
import Me from './components/Me.vue'
import Informations from './components/Informations.vue'
</script>

<template>
  <header>
    <img alt="Main logoass" class="logo" src="./assets/hordelogo.png" height="380" width="220"/>

    <div class="wrapper">
      <Me msg="Cristhian Peverelli" />
    </div>
  </header>

  <main>
    <Informations />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
