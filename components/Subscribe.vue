<template>
  <v-container id="subscribe" tag="section">
    <Base-card color="rgba(203, 170, 92, 0.51)" class="pa-3">
      <v-container grid-list-xl pa-0>
        <v-layout wrap>
          <v-flex xs12 md5>
            <BaseSubheading class="mb-3">Subscribe</BaseSubheading>
            <p>
              Enter your email address to subscribe to this blog and receive
              notifications of new posts by email.
            </p>

            <v-layout wrap pa-2>
              <v-text-field solo hide-details style="max-width: 400px;" />
              <v-btn
                :block="$vuetify.breakpoint.xsOnly"
                class="ma-0"
                color="secondary"
                style="height: 48px"
                >Subscribe</v-btn
              >
            </v-layout>
          </v-flex>
        </v-layout>
      </v-container>
    </Base-card>
  </v-container>
</template>

<script>
import BaseCard from "~/components/BaseCard.vue";
import BaseSubheading from "~/components/BaseSubheading.vue";

export default {
  components: {
    BaseCard,
    BaseSubheading
  }
};
</script>
