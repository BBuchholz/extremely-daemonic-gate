<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Welcome to Jacob's Salvage Yard, in the Darkest Heart of Shepton, WI.</p>
    <p>
      My establishment is located in a one-of-a-kind Liminal Space for those
      seeking to acquire or dispose of assets that transcend traditional
      definitions of Place and Time.
    </p>
    <p>
      As a sole proprietor, I take great pride in providing appraisal services
      for everything from a few curious discoveries to entire estate sales.
      Whether you're looking to sell off your old digital tinkerings or pass
      down your family's generational curses, Jacob's Salvage Yard can assist
      you in the process (no questions asked, and you don't have to explain
      anything you don't want to, I don't judge, on principle...)
    </p>
    <p>
      In addition to My Appraisal Services, I also broker deals with local
      builders to find new homes for old assets. I believe in repurposing and
      upcycling, and I strive to find new life for the items that pass through
      my doors.
    </p>
    <p>
      At Jacob's Salvage Yard, It is Understood, that each item holds its own
      unique story and value. I take time to carefully evaluate and assess each
      piece, personally, ensuring that you receive a fair and accurate
      appraisal.
    </p>
    <p>
      So come on down to Jacob's Salvage Yard (By Appointment ONLY!) and explore
      my Vast Collection of physical, digital, ideological, and spiritual
      curiosities.
    </p>
    <p>You never know what treasures you might find.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
