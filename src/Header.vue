<template>
  <header>
    <h2>Hello from a Vue Component</h2>
    <p>{{ parameter }}</p>
    <button @click="handleClick()" :style="{ background: bgColor }">Click me</button>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    parameter: String,
    bgColor: String,
  },
  methods: {
    handleClick() {
      console.log("Button clicked");
    },
  },
};
</script>

<style>
p {
  color: chocolate;
}
</style>
