<script setup lang="ts">
const model = defineModel();
</script>

<template>
<label>
<span>Adjust View</span>
<input v-model.number="model" type="range" min="3" max="24" step="1"/>
</label>

</template>

<style scoped>
label {
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  margin: 2rem 0;
  grid-gap: 1rem;
}

input {
  flex: 1;
}
</style>
