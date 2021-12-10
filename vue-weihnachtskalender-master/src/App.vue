<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  components: {
    // imported Components go here
  },

  data() {
    return {
      // reactive data goes here
    };
  },

  methods: {
    // methods go here
  },
});
</script>

<template>
  <h1>Weihnachtskalender 2021</h1>
  <div class="calendar">
    <!-- Here goes the WindowComponents -->
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Mountains+of+Christmas:wght@700&display=swap");

#app {
  font-family: "Mountains of Christmas", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 10px;
}

/* This creates a 6x4 grid with 140px wide squares */
.calendar {
  display: grid;
  grid-template-columns: repeat(6, 140px);
  grid-template-rows: repeat(4, 140px);
  gap: 20px;
}
</style>
