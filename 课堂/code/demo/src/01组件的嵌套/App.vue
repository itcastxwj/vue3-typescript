<template>
  <div id="app">
    <div class="header">
      <main></main>
      <component :is="asdasd"></component>
    </div>
  </div>
</template>

<script>
import main from "./main.vue";
export default {
  components: { main },
  data() {
    return {};
  },
};
</script>

<style scoped>
</style>