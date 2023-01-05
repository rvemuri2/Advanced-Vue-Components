<template>
  <p>Hey!</p>
  <button type="button" @click="age++">Update Age</button>
  <Greeting :age="age"> </Greeting>
  <User :age="age"></User>
</template>

<script>
import Greeting from "@/components/Greeting.vue";
import User from "@/components/User.vue";
export default {
  name: "App",
  components: {
    Greeting,
    User,
  },
  data() {
    return {
      age: 20,
    };
  },
};
</script>

<style scoped></style>
