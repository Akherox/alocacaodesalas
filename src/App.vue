<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header>
      <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container">
    <RouterLink to="/" class="navbar-brand">Alocação de Salas</RouterLink>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <RouterLink to="/" class="nav-link active" aria-current="page">Alocação</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link" to="/about">Salas</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link" to="/about">Usuarios</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink class="nav-link" to="/about">Sair</RouterLink>
        </li>
      </ul>
    </div>
  </div>
</nav>

  </header>
<main>
  <RouterView />
</main>
  
</template>

<style>

</style>
