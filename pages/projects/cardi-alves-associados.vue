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
      <h4 class="text--lighten-2">Projeto</h4>
      <h1 class="righteous">Site Institucional</h1>
      <h2>Escritório de advocacia</h2>
      <v-btn
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="#"
        target="_blank"
      >
        <v-icon dark> mdi-link-variant </v-icon>
      </v-btn>
      <v-divider class="pa-1"></v-divider>
      <h3>Sobre o projeto</h3>
      <p>
        O cliente já tinha um site, porém estava antigo e precisava de um rebranding. Além de precisar ser responsivo.
      </p>
      <v-divider class="pa-1"></v-divider>
      <h3>Screenshots</h3>
      <p>Algumas imagens da aplicação.</p>
      <v-row class="d-flex mb-1">
        <v-col cols="6">
          <v-img src="/screenshots/ceaa-mobile-desk.png" class="rounded"></v-img>
        </v-col>
        <v-col cols="6">
          <v-img src="/screenshots/ceaa-desk.png" class="rounded"></v-img>
        </v-col>
      </v-row>
      <v-divider class="pa-1"></v-divider>
      <h3>Tecnologias</h3>
      <p>Tecnologias as quais utilizamos para criação do projeto.</p>
      <v-item-group
        mandatory
        class="d-flex align-center justify-center flex-wrap"
      >
        <v-item class="fade">
          <img src="/technologies/vuejs.svg">
        </v-item>
        <v-item class="fade">
          <img src="/technologies/vuetify.svg">
        </v-item>
        <v-item class="fade">
          <img src="/technologies/figma.svg">
        </v-item>
      </v-item-group>
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {
  name: "ProjectTwo",
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
