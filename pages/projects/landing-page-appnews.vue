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
      <h1 class="righteous">Landing Page</h1>
      <h2>Página sobre um aplicativo</h2>
      <v-btn
        color="bg"
        small
        fab
        class="ma-2 mb-4 text-decoration-none"
        href="#"
      >
        <!-- target="_blank" -->
        <v-icon dark> mdi-link-variant </v-icon>
      </v-btn>
      <v-divider class="pa-1"></v-divider>
      <h3>Sobre o projeto</h3>
      <p>
        Foco em demonstração do produto e, consequentemente, aumentar o número
        de usuários.
      </p>
      <v-divider class="pa-1"></v-divider>
      <h3>Screenshots</h3>
      <p>Algumas imagens da aplicação.</p>
      <v-row class="d-flex mb-1">
        <v-col cols="4">
          <v-img src="/screenshots/lp-appnews1.png" class="rounded"></v-img>
        </v-col>
        <v-col cols="4">
          <v-img src="/screenshots/lp-appnews3.png" class="rounded"></v-img>
        </v-col>
        <v-col cols="4">
          <v-img src="/screenshots/lp-appnews2.png" class="rounded"></v-img>
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
          <svg
            width="84"
            height="91"
            viewBox="0 0 84 91"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g filter="url(#filter0_d_46_226)">
              <path
                d="M74.1146 58.3032V26.6968C74.1132 25.3111 73.7474 23.9502 73.0539 22.7505C72.3605 21.5509 71.3638 20.5547 70.1638 19.8619L42.5081 4.05862C41.3069 3.3651 39.9443 3 38.5573 3C37.1703 3 35.8077 3.3651 34.6065 4.05862L6.95081 19.8619C5.7508 20.5547 4.75408 21.5509 4.06064 22.7505C3.3672 23.9502 3.00142 25.3111 3 26.6968V58.3032C3.00142 59.6889 3.3672 61.0498 4.06064 62.2495C4.75408 63.4491 5.7508 64.4453 6.95081 65.1381L34.6065 80.9414C35.8077 81.6349 37.1703 82 38.5573 82C39.9443 82 41.3069 81.6349 42.5081 80.9414L70.1638 65.1381C71.3638 64.4453 72.3605 63.4491 73.0539 62.2495C73.7474 61.0498 74.1132 59.6889 74.1146 58.3032Z"
                fill="#171717"
                stroke="#171717"
                stroke-opacity="0.3"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M51.7656 27.5977H44.3438L38.875 36.1914L34.1875 27.5977H17L38.875 65L60.75 27.5977H51.7656ZM22.3711 30.7227H27.6445L38.875 50.0586L50.0078 30.7227H55.2812L38.875 58.8477L22.3711 30.7227Z"
                fill="#71B96A"
              />
            </g>
            <defs>
              <filter
                id="filter0_d_46_226"
                x="0"
                y="0"
                width="83.1146"
                height="91"
                filterUnits="userSpaceOnUse"
                color-interpolation-filters="sRGB"
              >
                <feFlood flood-opacity="0" result="BackgroundImageFix" />
                <feColorMatrix
                  in="SourceAlpha"
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                  result="hardAlpha"
                />
                <feOffset dx="3" dy="3" />
                <feGaussianBlur stdDeviation="2.5" />
                <feComposite in2="hardAlpha" operator="out" />
                <feColorMatrix
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
                />
                <feBlend
                  mode="normal"
                  in2="BackgroundImageFix"
                  result="effect1_dropShadow_46_226"
                />
                <feBlend
                  mode="normal"
                  in="SourceGraphic"
                  in2="effect1_dropShadow_46_226"
                  result="shape"
                />
              </filter>
            </defs>
          </svg>
        </v-item>
        <v-item class="fade">
          <svg
            width="84"
            height="91"
            viewBox="0 0 84 91"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g filter="url(#filter0_d_46_232)">
              <path
                d="M74.1146 58.3032V26.6968C74.1132 25.3111 73.7474 23.9502 73.0539 22.7505C72.3605 21.5509 71.3638 20.5547 70.1638 19.8619L42.5081 4.05862C41.3069 3.3651 39.9443 3 38.5573 3C37.1703 3 35.8077 3.3651 34.6065 4.05862L6.95081 19.8619C5.7508 20.5547 4.75408 21.5509 4.06064 22.7505C3.3672 23.9502 3.00142 25.3111 3 26.6968V58.3032C3.00142 59.6889 3.3672 61.0498 4.06064 62.2495C4.75408 63.4491 5.7508 64.4453 6.95081 65.1381L34.6065 80.9414C35.8077 81.6349 37.1703 82 38.5573 82C39.9443 82 41.3069 81.6349 42.5081 80.9414L70.1638 65.1381C71.3638 64.4453 72.3605 63.4491 73.0539 62.2495C73.7474 61.0498 74.1132 59.6889 74.1146 58.3032Z"
                fill="#171717"
                stroke="#171717"
                stroke-opacity="0.3"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M43.0156 38.7812C43.0156 37.0625 41.7656 36.125 39.6562 36.125H35.75V41.6719H39.0312C41.6094 41.6719 43.0156 40.5781 43.0156 38.7812ZM57.3906 37.7656C56.6094 35.3438 56.5312 32.375 56.6094 30.1094C56.6875 27.6875 54.8125 25.5 52.3125 25.5H26.6094C24.1094 25.5 22.2344 27.7656 22.3906 30.1094C22.4688 32.375 22.3125 35.3438 21.6094 37.7656C20.8281 40.1875 19.5781 41.75 17.5469 41.9062V44.1719C19.5781 44.3281 20.8281 45.8906 21.6094 48.3125C22.3125 50.7344 22.4688 53.7031 22.3906 55.9688C22.2344 58.3125 24.1094 60.5 26.6094 60.5H52.3125C54.8125 60.5 56.6875 58.3125 56.6094 55.9688C56.5312 53.7031 56.6094 50.7344 57.3125 48.3125C58.0938 45.8906 59.3438 44.3281 61.4531 44.1719V41.9062C59.3438 41.75 58.0938 40.1875 57.3906 37.7656ZM40.4375 52.375H32.7812V33.7031H40.3594C43.7969 33.7031 45.9844 35.5781 45.9844 38.3906C45.9844 40.3438 44.5 42.1406 42.5469 42.375V42.5312C45.2031 42.7656 46.9219 44.5625 46.9219 47.0625C46.9219 50.3438 44.5 52.375 40.4375 52.375ZM39.6562 43.8594H35.75V49.9531H39.8125C42.4688 49.9531 43.875 48.9375 43.875 46.9062C43.875 44.875 42.4688 43.8594 39.6562 43.8594Z"
                fill="#7309F9CF"
              />
            </g>
            <defs>
              <filter
                id="filter0_d_46_232"
                x="0"
                y="0"
                width="83.1146"
                height="91"
                filterUnits="userSpaceOnUse"
                color-interpolation-filters="sRGB"
              >
                <feFlood flood-opacity="0" result="BackgroundImageFix" />
                <feColorMatrix
                  in="SourceAlpha"
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                  result="hardAlpha"
                />
                <feOffset dx="3" dy="3" />
                <feGaussianBlur stdDeviation="2.5" />
                <feComposite in2="hardAlpha" operator="out" />
                <feColorMatrix
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
                />
                <feBlend
                  mode="normal"
                  in2="BackgroundImageFix"
                  result="effect1_dropShadow_46_232"
                />
                <feBlend
                  mode="normal"
                  in="SourceGraphic"
                  in2="effect1_dropShadow_46_232"
                  result="shape"
                />
              </filter>
            </defs>
          </svg>
        </v-item>
        <v-item class="fade">
          <svg
            width="84"
            height="91"
            viewBox="0 0 84 91"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g filter="url(#filter0_d_134_2)">
              <path
                d="M74.1146 58.3032V26.6968C74.1132 25.3111 73.7474 23.9502 73.0539 22.7505C72.3605 21.5509 71.3638 20.5547 70.1638 19.8619L42.5081 4.05862C41.3069 3.3651 39.9443 3 38.5573 3C37.1703 3 35.8077 3.3651 34.6065 4.05862L6.95081 19.8619C5.7508 20.5547 4.75408 21.5509 4.06064 22.7505C3.3672 23.9502 3.00142 25.3111 3 26.6968V58.3032C3.00142 59.6889 3.3672 61.0498 4.06064 62.2495C4.75408 63.4491 5.7508 64.4453 6.95081 65.1381L34.6065 80.9414C35.8077 81.6349 37.1703 82 38.5573 82C39.9443 82 41.3069 81.6349 42.5081 80.9414L70.1638 65.1381C71.3638 64.4453 72.3605 63.4491 73.0539 62.2495C73.7474 61.0498 74.1132 59.6889 74.1146 58.3032Z"
                fill="#171717"
                stroke="#171717"
                stroke-opacity="0.3"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M25 30.5C25 33.1562 26.3281 35.4219 28.3594 36.75C26.3281 38.1562 25 40.4219 25 43.0781C25 45.6562 26.3281 47.9219 28.3594 49.3281C26.3281 50.6562 25 52.9219 25 55.5781C25 59.7188 28.3594 63 32.5 63C36.6406 63 40.0781 59.6406 40.0781 55.5V48.5469C41.4062 49.7969 43.2031 50.5 45.1562 50.5H45.3125C49.4531 50.5 52.7344 47.1406 52.7344 43.0781C52.7344 40.4219 51.4062 38.1562 49.375 36.75C51.4062 35.4219 52.7344 33.1562 52.7344 30.5C52.7344 26.3594 49.4531 23 45.3125 23H32.4219C28.2812 23 25 26.3594 25 30.5ZM37.6562 38V48.0781H32.4219C29.6094 48.0781 27.4219 45.8125 27.4219 43.0781C27.4219 40.2656 29.6875 38 32.4219 38H37.6562ZM40.0781 43.0781C40.0781 40.2656 42.3438 38 45.1562 38H45.3125C48.0469 38 50.3125 40.2656 50.3125 43.0781C50.3125 45.8125 48.0469 48.0781 45.3125 48.0781H45.1562C42.3438 48.0781 40.0781 45.8125 40.0781 43.0781ZM32.4219 50.5H37.6562V55.5C37.6562 58.3125 35.3125 60.5781 32.5 60.5781C29.6875 60.5781 27.4219 58.3125 27.4219 55.5781C27.4219 52.7656 29.6094 50.5781 32.4219 50.5ZM32.4219 25.5H37.6562V35.5781H32.4219C29.6875 35.5781 27.4219 33.3125 27.4219 30.5C27.4219 27.7656 29.6875 25.5 32.4219 25.5ZM40.0781 35.5781V25.5H45.3125C48.0469 25.5 50.3125 27.7656 50.3125 30.5C50.3125 33.3125 48.0469 35.5781 45.3125 35.5781H40.0781Z"
                fill="url(#paint0_linear_134_2)"
                fill-opacity="0.77"
              />
            </g>
            <defs>
              <filter
                id="filter0_d_134_2"
                x="0"
                y="0"
                width="83.1146"
                height="91"
                filterUnits="userSpaceOnUse"
                color-interpolation-filters="sRGB"
              >
                <feFlood flood-opacity="0" result="BackgroundImageFix" />
                <feColorMatrix
                  in="SourceAlpha"
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                  result="hardAlpha"
                />
                <feOffset dx="3" dy="3" />
                <feGaussianBlur stdDeviation="2.5" />
                <feComposite in2="hardAlpha" operator="out" />
                <feColorMatrix
                  type="matrix"
                  values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
                />
                <feBlend
                  mode="normal"
                  in2="BackgroundImageFix"
                  result="effect1_dropShadow_134_2"
                />
                <feBlend
                  mode="normal"
                  in="SourceGraphic"
                  in2="effect1_dropShadow_134_2"
                  result="shape"
                />
              </filter>
              <linearGradient
                id="paint0_linear_134_2"
                x1="30.5"
                y1="25"
                x2="43.5"
                y2="54"
                gradientUnits="userSpaceOnUse"
              >
                <stop stop-color="#EE0D0D" />
                <stop
                  offset="0.286458"
                  stop-color="#F07B0E"
                  stop-opacity="0.9"
                />
                <stop
                  offset="0.541667"
                  stop-color="#7309F9"
                  stop-opacity="0.81"
                />
                <stop offset="0.744792" stop-color="#2298BD" />
                <stop offset="1" stop-color="#71B96A" />
              </linearGradient>
            </defs>
          </svg>
        </v-item>
      </v-item-group>
    </v-card-text>
  </v-card>
  <!-- background: rgba(254, 251, 251, 0.35) -->
</template>

<script>
export default {
  name: "LandingPageAppNews",
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
