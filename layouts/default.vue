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
  }
};
</script>
<style lang="scss">
html {
  background-color: red;
}
</style>
