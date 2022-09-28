<template>
  <v-app dark class="app">
    <v-app-bar color="transparent" elevation="0" class="pt-8">
      <Logo />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <!-- :absolute="!fixed" -->
    <v-footer color="transparent" dark class="mb-5">
      <Menu />
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {
      /* fixed: false, */
    };
  },
};
</script>
<style lang="sass">
#app
  background: url('/background/bg-blur.svg') no-repeat center
  background-size: cover

.v-toolbar__content
  justify-content: center,
</style>