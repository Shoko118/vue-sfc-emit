<template>
  <button @click="getOpenButton">Open the damn button</button>
</template>

<script setup>
const emit = defineEmits(["openButton"]);
function getOpenButton() {
  emit("openButton");
}
</script>
