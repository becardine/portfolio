<template>
  <v-row>
    <v-col align="center">
      <v-card
        :value="value"
        color="bg"
        class="rounded-pill d-flex justify-center align-center"
        :min-height="$vuetify.breakpoint.md ? '84px' : '84px'"
        max-width="342px"
      >
        <v-btn
          value=1
          class="mx-2 align-center"
          :class="this.$route.name === 'projects-1' ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          color="blue-grey lighten-5"
          height="47px"
          width="47px"
          @click="$router.push('/projects/1')"
        >
          <v-img src="/icones/code.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=2
          class="mx-2"
          :class="this.$route.name === 'projects-2' ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          color="blue-grey lighten-5"
          height="47px"
          width="47px"
          @click="$router.push('/projects/2')"
        >
          <v-img src="/icones/code.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=0
          class="mx-2 align-center"
          :class="this.$route.name === 'about' ? 'is-active' : ''"
          elevation="2"
          transition="fade"
          fab
          dark
          color="grey lighten-4"
          height="47px"
          width="47px"
          @click="$router.push('/about')"
        >
          <v-img
            src="/icones/logo-menu.svg"
            max-width="30px"
            class="ml-1"
          ></v-img>
        </v-btn>
        <v-btn
          value=3
          class="mx-2"
          :class="this.$route.name === 'projects-3' ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          color="blue-grey lighten-5"
          height="47px"
          width="47px"
          @click="$router.push('/projects/3')"
        >
          <v-img src="/icones/code.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=4
          class="mx-2"
          :class="this.$route.name === 'projects-4' ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          color="blue-grey lighten-5"
          height="47px"
          width="47px"
          @click="$router.push('/projects/4')"
        >
          <v-img src="/icones/code.svg" max-width="30px"></v-img>
        </v-btn>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  data() {
    return {
      value: null,
    };
  },
};
</script>

<style scoped>
.is-active {
  -webkit-animation: is-active 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
  animation: is-active 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
  scale: 1.3;
}
@-webkit-keyframes is-active {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 35% 35%;
    transform-origin: 35% 35%;
    text-shadow: none;
  }
  100% {
    -webkit-transform: translateY(-35px);
    transform: translateY(-35px);
    -webkit-transform-origin: 35% 35%;
    transform-origin: 35% 35%;
    text-shadow: 0 1px 0 #cccccc, 0 2px 0 #cccccc, 0 3px 0 #cccccc,
      0 4px 0 #cccccc, 0 5px 0 #cccccc, 0 6px 0 #cccccc, 0 7px 0 #cccccc,
      0 8px 0 #cccccc, 0 9px 0 #cccccc, 0 35px 30px rgba(0, 0, 0, 0.3);
  }
}
@keyframes is-active {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 35% 35%;
    transform-origin: 35% 35%;
    text-shadow: none;
  }
  100% {
    -webkit-transform: translateY(-35px);
    transform: translateY(-35px);
    -webkit-transform-origin: 35% 35%;
    transform-origin: 35% 35%;
    text-shadow: 0 1px 0 #cccccc, 0 2px 0 #cccccc, 0 3px 0 #cccccc,
      0 4px 0 #cccccc, 0 5px 0 #cccccc, 0 6px 0 #cccccc, 0 7px 0 #cccccc,
      0 8px 0 #cccccc, 0 9px 0 #cccccc, 0 35px 30px rgba(0, 0, 0, 0.3);
  }
}
</style>