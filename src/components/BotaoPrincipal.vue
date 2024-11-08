<script lang="ts">
export default {
  props: {
    texto: { type: String, required: true },
  },
};
</script>

<template>
  <button class="botao-principal">{{ texto }}</button>
</template>

<style scoped>
.botao-principal {
  background: var(--coral);
  color: var(--branco);
  font-weight: 600;
  font-size: 18px;
  padding: 12px 34px;
  border-radius: 24px;
  cursor: pointer;
}
</style>
