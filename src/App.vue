<template>
  <v-app>
    <navbar />
    <v-content>
      <router-view></router-view>
    </v-content>

    <v-main> </v-main>
  </v-app>
</template>

<script>
import navbar from "./components/navbar";

export default {
  name: "App",

  components: {
    navbar
  },

  data: () => ({
    //
  })
};
</script>
