<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Button @openButton="openButton" />
</template>

<script setup>
import { ref } from "vue";
import Button from "./components/Button.vue";

function openButton() {
  alert("From the damn child component button");
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
