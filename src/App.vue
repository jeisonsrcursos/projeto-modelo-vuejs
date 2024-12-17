<script setup>
  import Header from './components/Header.vue';
  import Footer from './components/Footer.vue';
  import Home from './pages/Home.vue';
</script>

<template>
  <Header />
  <main class="container">
    <!-- Conteúdo -->
    <Home titulo="BEM VINDO TURMA FE!!!"/>
  </main>
  <Footer rodape="Desenvolvido por: [NOME] 2024&copy;" />
</template>

<style scoped>
</style>
