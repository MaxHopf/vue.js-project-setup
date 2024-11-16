<template>
  <header>
    <h2>Hello from a Vue Component</h2>
    <p>{{ parameter }}</p>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    parameter: String,
  },
};
</script>

<style></style>
