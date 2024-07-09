<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <v-app-bar-nav-icon></v-app-bar-nav-icon>

    <v-toolbar-title>👋 Hello World 🌎</v-toolbar-title>
  </v-app-bar>

    <v-main>
      <TopClerks/>
    </v-main>
  </v-app>
</template>

<script>
import TopClerks from './components/TopClerks';

export default {
  name: 'App',

  components: {
    TopClerks,
  },

  data: () => ({
    //
  }),
};
</script>
