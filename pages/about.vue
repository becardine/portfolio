<template>
  <v-card
    class="ma-auto pa-3 card-content overflow-auto"
    max-width="500px"
    max-height="600px"
    transition="fab-transition"
  >
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
      <v-btn
        type="button"
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="https://api.whatsapp.com/send?phone=5548998687810&text=Ol%C3%A1!%20Vim%20do%20site%20do%20seu%20portf%C3%B3lio%20e%20gostaria%20de%20um%20or%C3%A7amento!"
        target="_blank"
      >
        <v-icon dark> mdi-whatsapp </v-icon>
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
      <v-divider class="pa-1"></v-divider>
      <h3>Entre em contato</h3>
      <p class="mb-1">Vamos conversar sobre seu projeto.</p>
      <v-btn
        type="button"
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="https://api.whatsapp.com/send?phone=5548998687810&text=Ol%C3%A1!%20Vim%20do%20site%20do%20seu%20portf%C3%B3lio%20e%20gostaria%20de%20um%20or%C3%A7amento!"
        target="_blank"
      >
        <v-icon dark> mdi-whatsapp </v-icon>
      </v-btn>
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {
  name: "About",
  layout: "main",
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
