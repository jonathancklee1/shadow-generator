<template>
  <button
    class="mt-4 w-full border-2 border-secondary-background bg-primary-background p-4 text-sm font-medium uppercase text-secondary-background shadow-solid transition-all hover:border-primary-background hover:bg-secondary-background hover:text-primary-background focus:translate-x-0 focus:translate-y-1 lg:mt-0"
    @click="store.addShadow"
  >
    + Add Shadow
  </button>
</template>

<script setup lang="ts">
import { useShadowStore } from "../stores/ShadowStore";
const store = useShadowStore();
</script>

<style lang="scss" scoped></style>
