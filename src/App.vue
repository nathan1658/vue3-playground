<template>
  <div class="d-flex flex-column" style="height: 100vh">
    <SearchBar />
    <Carousell />
    <Menu2 />
    <VCard height="150" color="#f0f0f0" class="ma-3" />
    <VSpacer />
    <div style="height: 50px; width: 100%; background-color: grey"></div>
  </div>
</template>

<script lang="ts" setup>
import Carousell from "./components/Carousell.vue";
import SearchBar from "./components/SearchBar.vue";
import Menu2 from "./components/menu2.vue";
</script>

<style lang="css" scoped></style>
