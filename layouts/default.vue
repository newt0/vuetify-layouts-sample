<template>
  <v-app>
    <Header />
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <BottomNav />
    <Footer />
  </v-app>
</template>

<script>
import Footer from "~/components/Footer.vue";
import Header from "~/components/Header.vue";
import BottomNav from "~/components/BottomNav.vue";
export default {
  components: {
    Footer,
    Header,
    BottomNav
  },
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/"
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  }
};
</script>
