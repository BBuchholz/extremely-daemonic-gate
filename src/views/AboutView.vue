<template>
  <div class="about">
    <AboutLinks />
    <img
      alt="An AI Generated Image of Jacob in his BackRoom"
      src="../assets/Jacob_AI_BackRoom.jpg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import AboutLinks from "@/components/AboutLinks.vue"; // @ is an alias to /src

export default defineComponent({
  name: "AboutView",
  components: {
    AboutLinks,
  },
});
</script>
