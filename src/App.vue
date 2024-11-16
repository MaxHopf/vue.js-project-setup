<template>
  <h1>Hello from Vue.js Template</h1>
  <Header parameter="This is parameterized paragraph" />
</template>

<script>
import Header from "./Header.vue";
export default {
  name: "App",
  components: {
    Header,
  },
};
console.log("Hello from vue.js console");
</script>

<style>
#app {
  text-align: center;
}
h1 {
  color: brown;
}
</style>
