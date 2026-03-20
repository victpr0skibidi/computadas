<script setup>
import { ref } from 'vue'
const nome = ref('')
const sobrenome= ref('')

const nomeCompleto= () => {
  console.log('Calculando nome com função')
  return `${nome.value} ${sobrenome.value}`
  }
</script>

<template>
  <div class="conteiner">
    <input type="text" v-model1="nome" placeholder="Nome">
    <input type="text" v-model1="sobrenome" placeholder="Sobrenome">
    <label> {{ nomeCompleto() }}</label>
    <input type="text" v-model="texto">

  </div>
</template>

<style scoped>
</style>
