<template>
  <v-app dark class="app">
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
<style lang="sass" >
  #app
    background: url('/background/bg-blur.svg') no-repeat center
    background-size: cover
</style>