<template>
  <v-row>
    <v-col lg="6" md="4" offset-md="4" offset-lg="3">
      <v-card
        :value="value"
        color="primary"
        class="rounded-pill d-flex justify-center align-center"
        :min-height="$vuetify.breakpoint.md ? '8.2vh' : '7vh'"
      >
        <v-btn
          value=1
          class="mx-2 align-center"
          :class="value == 1 ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          height="47px"
          width="47px"
          @click="showProject(1)"
        >
          <v-img src="/icones/logo-projeto-1.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=2
          class="mx-2"
          :class="value == 2 ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          height="47px"
          width="47px"
          @click="showProject(2)"
        >
          <v-img src="/icones/logo-projeto-2.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=0
          class="mx-2 align-center"
          :class="value == 0 ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          height="47px"
          width="47px"
          @click="showProject(0)"
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
          :class="value == 3 ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          height="47px"
          width="47px"
          @click="showProject(3)"
        >
          <v-img src="/icones/logo-projeto-3.svg" max-width="30px"></v-img>
        </v-btn>
        <v-btn
          value=4
          class="mx-2"
          :class="value == 4 ? 'is-active' : ''"
          elevation="2"
          fab
          dark
          color="purple"
          height="47px"
          width="47px"
          @click="showProject(4)"
        >
          <v-img src="/icones/logo-projeto-4.svg" max-width="30px"></v-img>
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
  methods: {
    showProject(value) {
      this.value = value;
      if (value == 0) {
        this.$router.push('about');
      }
    }
  },
};
</script>

<style scoped>
.is-active {
  -webkit-animation: is-active 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
  animation: is-active 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
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