<template>
  <div id="app">
    <HeaderIndexVue />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeaderIndexVue from "@/components/HeaderIndex.vue";
export default defineComponent({
  components: { HeaderIndexVue },
});
</script>

<style scoped></style>
