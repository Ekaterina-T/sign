<script setup lang="ts">
import { ref } from 'vue'

const sign = ref(null)
</script>

<template>
  <section class="input-area">
    <label class="input-area__input">
      <span>Enter sign of arifmetical operation</span>
      <input type="text" id="number1" v-model="sign" />
    </label>
  </section>
</template>

<style scoped>
.input-area {
  display: flex;
  flex-direction: column;
  row-gap: 20px;
}

.input-area__input {
  display: flex;
  column-gap: 25px;
}
</style>
