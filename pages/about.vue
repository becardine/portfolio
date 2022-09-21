<template>
  <v-card class="ma-auto pa-3 card-content" max-width="500px">
    <v-card-text>
      <h3>Olá, eu sou a</h3>
      <h1>becardine</h1>
      <h2>Frontend developer</h2>
      <v-btn icon elevation="2" class="ma-2">
        <v-icon> mdi-github </v-icon>
      </v-btn>
      <v-btn icon elevation="2" class="ma-2">
        <v-icon> mdi-linkedin </v-icon>
      </v-btn>
      <v-divider></v-divider>
      <h2>Graduação</h2>
      <p>
        Graduanda em Analise e Desenvolvimento de Sistemas, que encontrou sua
        paixão na tecnologia. Além de estudar - <strong>muito</strong> - por
        conta.
      </p>
      <v-divider></v-divider>
      <h2>Jobs</h2>
      <p>
        Atuando full time no time de desenvolvimento de uma agência. E faço
        alguns freelas.
      </p>
      <v-divider></v-divider>
      <h2>Hard skills</h2>
      <p>Princípais tecnologias que trabalho atualmente.</p>
      <Technologies />
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {};
</script>

<style lang="sass" scoped>
.v-sheet.v-card
  border-radius: 30px
</style>