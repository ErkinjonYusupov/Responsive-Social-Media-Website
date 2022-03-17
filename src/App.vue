<template>
  <v-app>
      <v-main style="background:hsl(252,30%,95%)">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
