<script setup>
  defineProps({
    rodape: String,
  })
</script>
<template>
    <footer class="fixed-bottom text-center m-2">
      <!-- Rodapé -->
       <h3>{{ rodape }}</h3>
    </footer>
</template>
<style scope>
  h3 {
    font-size: 15px;
  }
</style>