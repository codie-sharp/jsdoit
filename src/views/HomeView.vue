<template>
  <div>
    <HelloClarice />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloClarice from "@/components/HelloClarice.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloClarice,
  },
});
</script>
