<template>
  <div class="d-flex py-3">
    <div
      v-for="n in items"
      :key="n"
      style="width: 100px"
      class="item d-flex flex-column align-center justify-center"
    >
      <div class="circle" />
      <div>
        {{ n }}
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
const items = ["二手好貨", "活動大促", "專題匯", "特賣會", "更多"];

export default defineComponent({
  name: "Menu2",

  setup(props) {
    return {
      items,
    };
  },
});
</script>

<style scoped lang="css">
.circle {
  height: 30px;
  width: 30px;
  background: #efd6b7;
  border-radius: 50%;
}
</style>
