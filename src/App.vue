<template>
  <v-app>
    <v-container class="pa-0" fluid>
      <v-system-bar height="31" dark color="primary">
        <v-row justify="center" no-gutters>
          <v-col cols="7">
            <a class="white--text" href="#">
              <v-icon color="white">mdi-email</v-icon>thomasprusso@gmail.com
              <v-icon class="ml-4" color="white">mdi-facebook</v-icon>
              <v-icon class="ml-4" color="white">mdi-instagram</v-icon>
            </a>
          </v-col>
        </v-row>
      </v-system-bar>
      <v-app-bar elevation="1">
        <v-row justify="center" no-gutters>
          <v-col cols="7"></v-col>
        </v-row>
      </v-app-bar>
    </v-container>
    <!-- <v-content></v-content> -->
  </v-app>
</template>

<style src="@/assets/css/main.scss" lang="scss"></style>
<script>
export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
