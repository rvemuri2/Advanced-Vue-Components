<template>
  <h1>Home Page</h1>
</template>

<script>
export default {
  unmounted() {
    console.log("It was unmounted");
  },
  activated() {
    console.log("Home comp is activated");
  },
  deactivated() {
    console.log("Home comp is de-activated");
  },
};
</script>
