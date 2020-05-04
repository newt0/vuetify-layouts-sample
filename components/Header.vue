<template>
  <v-card color="grey lighten-4" flat tile fluid>
    <v-toolbar dense>
      <v-toolbar-title style="min-width: 50px">
        <h1 v-if="this.$route.path === '/'">
          <v-img src="https://stayhomes.netlify.app/images/logo.png"></v-img>
        </h1>
        <p v-else class="mt-2">
          <nuxt-link to="/">
            <v-img src="https://stayhomes.netlify.app/images/logo.png"></v-img>
          </nuxt-link>
        </p>
      </v-toolbar-title>

      <v-tabs align-with-title grow style="min-width: auto">
        <v-tab>Tab 1</v-tab>
        <v-tab>Tab 2</v-tab>
        <v-tab>Tab 3</v-tab>
        <!-- <v-tab>Tab 4</v-tab>
        <v-tab>Tab 5</v-tab>-->
      </v-tabs>
    </v-toolbar>
  </v-card>
</template>
