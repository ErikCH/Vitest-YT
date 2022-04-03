<script setup lang="ts">
import View from "./components/View.vue";
import MyPokemon from "./components/my-pokemon.vue";
</script>

<template>
  <h2>Hello World</h2>
  <View element="div">Hello from view</View>
  <br />
  <my-pokemon></my-pokemon>
</template>

<style>
#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}
</style>
