<template>
  <v-row>
    <v-col lg6 xs12>
      <v-card class="mx-auto" outlined>
        <v-list-item three-line>
          <nuxt-link to="/post">
            <v-list-item-avatar
              tile
              size="80"
              color="grey"
            ></v-list-item-avatar>
          </nuxt-link>
          <v-list-item-content>
            <div class="overline mb-4">カテゴリー</div>
            <nuxt-link to="/post">
              <v-list-item-title class="headline mb-1"
                >記事の見出し</v-list-item-title
              >
            </nuxt-link>
            <v-list-item-subtitle
              >Greyhound divisely hello coldly
              fonwderfully</v-list-item-subtitle
            >
            <v-list-item-subtitle>５分で読めます</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-card>
    </v-col>
    <v-col lg6 xs12>
      <v-card class="mx-auto" outlined>
        <v-list-item three-line>
          <nuxt-link to="/blog">
            <v-list-item-avatar
              tile
              size="80"
              color="grey"
            ></v-list-item-avatar>
          </nuxt-link>
          <v-list-item-content>
            <div class="overline mb-4">カテゴリー</div>
            <nuxt-link to="/blog">
              <v-list-item-title class="headline mb-1"
                >記事の見出し</v-list-item-title
              >
            </nuxt-link>
            <v-list-item-subtitle
              >Greyhound divisely hello coldly
              fonwderfully</v-list-item-subtitle
            >
            <v-list-item-subtitle>５分で読めます</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-card>
    </v-col>
  </v-row>
</template>
