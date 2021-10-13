<template>
  <Milkdown />
</template>

<script>
import Milkdown from "./components/Milkdown.vue";
export default {
  name: "App",
  components: {
    Milkdown,
  },
};
</script>
<style>
body {
  background: rgba(var(--background), 1);
}
</style>