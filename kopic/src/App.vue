<template>
  <v-app>
    <home></home>
  </v-app>
</template>

<script>
import Home  from "./views/Home";

export default {
  name: "App",

  components: {
    Home
  },

  data: () => ({
    //
  })
};
</script>
