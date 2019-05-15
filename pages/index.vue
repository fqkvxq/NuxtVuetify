<template>
  <v-container>
    <v-layout column justify-center align-center>
      <v-flex xs12 sm8 md6>
        <logo/>
        <vuetify-logo/>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo
  }
};
</script>
