<template>
  <h1 class="text-3xl mb-4">
    <slot></slot>
  </h1>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "TitleHeading",
});
</script>
