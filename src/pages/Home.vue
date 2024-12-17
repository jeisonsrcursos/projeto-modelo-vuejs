<script setup>

    defineProps({
        titulo: String
    })

</script>
<template>
    <h1 class="text-center mt-5">{{ titulo }}</h1>
    <div class="container text-center">
        <img 
            src="../assets/img/paisagens/paisagem-1.jpg"
            alt="Imagem de uma paisagem."
            class="paisagem rounded">
    </div>
</template>
<style scope>
    .paisagem {
        width: 400px;
        height: auto;
        margin: 1rem;
    }
</style>