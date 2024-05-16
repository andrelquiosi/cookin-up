<template>
  <button class="botao-principal tag">
    Buscar Receitas! 
  </button>
</template>

<script lang="ts">
import Tag from './Tag.vue';

export default {
  components: {
    Tag
  }

};
</script>

<style scoped>
.botao-principal {
  display: flex;
  justify-content: center;
  gap: 0.5rem;
  flex-wrap: wrap;
  cursor: pointer;

}
.tag {
  display: inline-block;
  border-radius: 0.5rem;
  min-width: 4.25rem;
  padding: 0.5rem;
  text-align: center;
  transition: 0.2s;
  color: var(--cinza);
  background: var(--cinza-claro);
  font-weight: 400;
}

.tag.ativa {
  color: var(--creme, #fffaf3);
  background: var(--coral, #f0633c);
  font-weight: 700;
}
</style>
