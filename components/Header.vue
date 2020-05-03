<template>
  <v-card color="grey lighten-4" flat tile fluid>
    <v-toolbar dense>
      <v-toolbar-title>
        <!-- テキストを入れると崩れる原因は不明だが、画像入れれば問題ない -->
        <v-img src="https://stayhomes.netlify.app/images/logo.png"></v-img>
      </v-toolbar-title>

      <v-spacer></v-spacer>

      <v-tabs align-with-title grow>
        <v-tab>Tab 1</v-tab>
        <v-tab>Tab 2</v-tab>
        <v-tab>Tab 3</v-tab>
      </v-tabs>
    </v-toolbar>
  </v-card>
</template>
