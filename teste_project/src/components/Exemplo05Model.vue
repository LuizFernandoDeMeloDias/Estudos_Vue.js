
<script setup>

import {ref} from 'vue'

let texto = ref('');

</script>

<template>
    <div>
        <input type="text" v-model="texto">
        <p>{{ texto }}</p>  
    </div>
</template>