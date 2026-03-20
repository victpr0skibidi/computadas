<script setup>
import { ref } from 'vue'
const nome = ref('')
const sobrenome= ref('')

const nomeCompleto= () => {
  return `$(nome)`
}
</script>

<template>
  <div class="conteiner">
    <input type="text" v-model1="nome" placeholder="Nome">
    <input type="text" v-model1="sobrenome" placeholder="Sobrenome">
    <label> {{ nomeCompleto() }}</label>

  </div>
</template>

<style scoped>
</style>
