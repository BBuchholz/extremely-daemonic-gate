<template>
  <div class="home">
    <img alt="Jacob's Salvage Yard logo" src="../assets/JSY_LOGO.png" />
    <HelloWorld msg="A Message From Jacob" />
    <img
      alt="An AI Generated Image of Jacob in his CurioShop"
      src="../assets/Jacob_AI_CurioShop.jpg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
</style>
