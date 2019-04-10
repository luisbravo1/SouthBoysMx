<template>
  <v-app light>
    <v-toolbar class="white">
      <v-toolbar-title>SouthBoysMX</v-toolbar-title>
    </v-toolbar>
    <v-content>
      <section>
        <v-parallax src="https://instagram.fntr6-1.fna.fbcdn.net/vp/5af7b4ae012fcc94077c10200f6666c4/5D3F7363/t51.2885-15/e35/s1080x1080/51359130_2296353557250390_5870910124311727229_n.jpg?_nc_ht=instagram.fntr6-1.fna.fbcdn.net" height="600">
          <v-layout
            column
            align-center
            justify-center
            class="white--text"
          >
            <h1 class="white--text mb-2 display-1 text-xs-center">South Boys</h1>
            <div class="subheading mb-3 text-xs-center">@nueveochomx</div>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-layout
          wrap
          class="my-5"
          align-center
          justify-center
        >
          <v-flex xs12 sm4 class="my-3">
            <h2 class="headline text-xs-center">Nuestra Música</h2>
          </v-flex>
          <v-flex md12>
            <v-container fluid>
              <v-layout row justify-center>
                <v-flex md6 pa-3>
                  <v-card class="roundCard">
                    <div class="title mb-1 pa-3 text-xs-center">TiempoTiempoTiempo</div>
                    <v-layout column>
                      <v-img src="https://instagram.fntr6-1.fna.fbcdn.net/vp/3b39e77712a7ee017b8f3ebd8388b05e/5D492418/t51.2885-15/e35/51661776_355373681978429_1499270316318585751_n.jpg?_nc_ht=instagram.fntr6-1.fna.fbcdn.net" aspect-ratio="1"></v-img>
                    </v-layout>
                  </v-card>
                </v-flex>

                <v-flex md6 pa-3>
                  <v-card class="roundCard">
                    <div class="title mb-1 pa-3 text-xs-center">Sólo Ésta Vez</div>
                    <v-layout column>
                      <v-img src="https://instagram.fntr6-1.fna.fbcdn.net/vp/3b39e77712a7ee017b8f3ebd8388b05e/5D492418/t51.2885-15/e35/51661776_355373681978429_1499270316318585751_n.jpg?_nc_ht=instagram.fntr6-1.fna.fbcdn.net" aspect-ratio="1"></v-img>
                    </v-layout>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section>
        <v-layout
          column
          wrap
          class="my-5"
          align-center
        >
          <v-flex xs12 sm4 class="my-3">
            <div class="text-right">
              <h2 class="headline">About us</h2>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">color_lens</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Material Design</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">flash_on</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Fast development</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">build</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Completely Open Sourced</div>
                    </v-card-title>
                    <v-card-text>
                      Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                      Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                      Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section>
        <v-parallax src="https://instagram.fntr6-1.fna.fbcdn.net/vp/3b39e77712a7ee017b8f3ebd8388b05e/5D492418/t51.2885-15/e35/51661776_355373681978429_1499270316318585751_n.jpg?_nc_ht=instagram.fntr6-1.fna.fbcdn.net" height="380">
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-3 text-xs-center">Web development has never been easier</div>
            <em>Kick-start your application today</em>
            <v-btn
              class="blue lighten-2 mt-5"
              dark
              large
              href="/pre-made-themes"
            >
              Get Started
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Company info</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare. 
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. 
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti. 
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>81 1471 8696</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">music_note</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <a href="https://open.spotify.com/artist/21rIRFqMaONZIbIVRm02pM?si=0tVylLlET2W0dLLLo6O3OA">SouthBoys</a>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Monterrey, Nuevo León</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>nueveochomty@gmail.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>

      <v-footer class="blue darken-2">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              by <a class="white--text" href="https://www.instagram.com/nueveochomx/" target="_blank">@nueveochomx</a>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>

<style scoped>
.numbers {
  font-size: 2em;
  margin-bottom: 0px;
}
.vaMiddle {
  margin: auto;
}
.roundCard {
  border-radius: 7px;
}
.bold--title {
  font-weight: bold;
  font-size: 1.3em;
}
.bold--titleBig {
  padding: 0.5em;
  font-weight: bold;
  font-size: 2.5em;
}
</style>
