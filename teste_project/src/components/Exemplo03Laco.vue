
<script setup>

let nomes = ['joão', 'maria', 'julia']

</script>

<template>
    <ul>
        <li v-for="(n, index) in nomes" :key="index">{{index + 1}} {{ n }}</li>
    </ul>
</template>