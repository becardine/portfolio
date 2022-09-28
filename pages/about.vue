<template>
  <v-card class="ma-auto pa-3 card-content" max-width="500px" transition="fab-transition">
    <v-card-text>
      <v-row justify="end">
      <v-btn icon dark @click="$router.push('/')">
        <v-icon color="bg">mdi-close</v-icon>
      </v-btn>
      </v-row>
      <h4 class="text--lighten-2">Olá, eu sou a</h4>
      <h1 class="righteous">becardine</h1>
      <h2>Frontend developer</h2>
      <v-btn
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="https://github.com/becardine/"
        target="_blank"
      >
        <v-icon dark> mdi-github </v-icon>
      </v-btn>
      <v-btn
        type="button"
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="https://www.linkedin.com/in/becardine/"
        target="_blank"
      >
        <v-icon dark> mdi-linkedin </v-icon>
      </v-btn>
      <v-divider class="pa-1"></v-divider>
      <h3>Graduação</h3>
      <p>
        Graduanda em Analise e Desenvolvimento de Sistemas, que encontrou sua
        paixão na tecnologia. Além de estudar - <strong>muito</strong> - por
        conta.
      </p>
      <v-divider class="pa-1"></v-divider>
      <h3>Jobs</h3>
      <p>
        Atuando full time no time de desenvolvimento de uma agência. E faço
        alguns freelas.
      </p>
      <v-divider class="pa-1"></v-divider>
      <h3>Hard skills</h3>
      <p>Princípais tecnologias que trabalho atualmente.</p>
      <Technologies />
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {
  name: 'About',
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
