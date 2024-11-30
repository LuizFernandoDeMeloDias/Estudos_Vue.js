
<script setup>

let validacao = false

</script>

<style>
    .ok{color:forestgreen}

    .falha{color: red;}
</style>

<template>
    <p :class="validacao ? 'ok' : 'falha'">Utilizando a diretiva class.</p>
</template>