<template>
  <header>
    <h2>Hello from a Vue Component</h2>
    <p>{{ parameter }}</p>
    <button :style="{ background: bgColor }">Click me</button>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    parameter: String,
    bgColor: String,
  },
};
</script>

<style>
p {
  color: chocolate;
}
</style>
