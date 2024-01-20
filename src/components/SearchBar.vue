<template>
  <div class="pa-3">
    <VTextField label="商品搜索" variant="outlined" density="compact">
      <template v-slot:prepend>
        <v-icon :color="model ? 'primary' : undefined" icon="mdi-magnify" />
      </template>
    </VTextField>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
.v-text-field--outlined >>> fieldset {
  border-color: rgba(192, 0, 250, 0.986);
}
</style>
