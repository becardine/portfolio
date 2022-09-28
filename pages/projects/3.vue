<template>
  <v-card
    class="ma-auto pa-3 card-content"
    max-width="500px"
    transition="fab-transition"
  >
    <v-card-text>
      <v-row justify="end">
        <v-btn icon dark @click="$router.push('/')">
          <v-icon color="primary">mdi-close</v-icon>
        </v-btn>
      </v-row>
      <h4 class="text--lighten-2 mb-10">Projeto</h4>
        <v-img src="/icones/code.svg"></v-img>
        <h2 align="center" class="mt-15">Em construção...</h2>
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {
  name: "ProjectThree",
  layout: 'main',

};
</script>

<style lang="sass" scoped>
.v-sheet.v-card
  border-radius: 30px
  background: rgba(254, 251, 251, 0.35)

h1
  font-weight: 900,

h3
  font-weight: 100,
  opacity: 0.1,
  z-index: -1,
p
  color: black,
  z-index: 999,
  margin-top: -1rem,
</style>
