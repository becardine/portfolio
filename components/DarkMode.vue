<template>
  <v-container class="mt-5 text-end dark">
    <v-btn icon v-if="$vuetify.theme.dark" @click="toggleTheme()">
      <v-icon
        transition="scroll-x-transition"
        class="ml-5 material-icons"
        color="blue-grey darken-4"
        >dark_mode</v-icon
      >
    </v-btn>
    <v-btn icon v-if="!$vuetify.theme.dark" @click="toggleTheme()">
      <v-icon
        transition="scale-transition"
        origin="center center"
        color="yellow darken-3"
        class="mr-5 pa-0"
        >light_mode</v-icon
      >
    </v-btn>
  </v-container>
</template>

<script>
export default {
  methods: {
    toggleTheme() {
      this.$vuetify.theme.dark = !this.$vuetify.theme.dark;
    },
  },
};
</script>

