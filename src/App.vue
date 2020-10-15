<template>
  <v-app>
    <v-app-bar
      app
      color="#D1C2BF"
      clipped-left
      flat
    >
      <v-card width="30vh" dark class="pt-14" color="#2A2A2A">
        <v-card-text align="center">Loggan ska vara här</v-card-text>
      </v-card>
      <v-spacer></v-spacer>

      <v-tabs color="#2A2A2A" fixed-tabs>
        <v-tab>
          Start
        </v-tab>
        <v-tab target="_blank">
          Produkter
        </v-tab>
        <v-tab target="_blank" color="rgb(255,255,255,0.3)">
          Återförsäljare
        </v-tab>
        <v-tab target="_blank" color="rgb(255,255,255,0.3)">
          Om oss
        </v-tab>
        <v-tab target="_blank" color="rgb(255,255,255,0.3)">
          Kontakt
        </v-tab>
        <v-tab target="_blank" color="rgb(255,255,255,0.3)">
          Hjälp
        </v-tab>
      </v-tabs>

<!--      <v-btn target="_blank" color="rgb(255,255,255,0.3)">Produkter</v-btn>-->
<!--      <v-spacer></v-spacer>-->

<!--      <v-btn target="_blank" color="rgb(255,255,255,0.3)">Återförsäljare</v-btn>-->
<!--      <v-spacer></v-spacer>-->

<!--      <v-btn target="_blank" color="rgb(255,255,255,0.3)">Om oss</v-btn>-->
<!--      <v-spacer></v-spacer>-->

<!--      <v-btn target="_blank" color="rgb(255,255,255,0.3)">Kontakt</v-btn>-->
<!--      <v-spacer></v-spacer>-->

<!--      <v-btn target="_blank" color="rgb(255,255,255,0.3)">Hjälp</v-btn>-->
<!--      <v-spacer></v-spacer>-->

    </v-app-bar>

    <v-navigation-drawer
        permanent
        app
        clipped
    >
      <v-list>
        <v-list-item class="pt-4">
          <v-list-item-content>
            <v-list-item-title class="title">
              Hanna Edlund
            </v-list-item-title>
            <v-list-item-subtitle>hanna@edlunds.biz</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-list>

      <v-divider></v-divider>
      <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Nibh sed pulvinar proin gravida. Risus nullam eget felis eget. Ultricies lacus sed turpis tincidunt id aliquet risus feugiat in. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse.</v-card-text>
      <v-card-text>Ac turpis egestas maecenas pharetra convallis posuere morbi leo urna. Est lorem ipsum dolor sit amet consectetur. Dui vivamus arcu felis bibendum ut tristique et. Fermentum odio eu feugiat pretium nibh ipsum consequat nisl.</v-card-text>

      <v-list
          nav
          dense
      >
        <v-list-item link href="https://github.com/Meriono" target="_blank">
          <v-list-item-icon>
            <v-icon>mdi-github</v-icon>
          </v-list-item-icon>
          <v-list-item-title>My GitHub</v-list-item-title>
        </v-list-item>
        <v-list-item link href="https://previews.dropbox.com/p/thumb/AA_SAkBY8xnT87eXLTE815-rg8UiDu6x2V9BsmDYYtHk4v7r9jcVmcMS6xNBrPL3tPKa21EYYcoli6aGP3G0hXKE8nXankxidMGi2jouFg1lT_GTI8RdREghcRv6J4lCGf_6VsSdfePZhdRdwWBu10Mob_VN65-_8l2M-Dnr803UoEjsZkpj77PWB9ijjCUHJAQdtsdXx837BaldWC7tVKmelLj5P7yu5cHVov-1QNRX41gS_kOMS3oJaleP2rTs1e2LPqVmAkVIoetFe9FpQjg36ieFJNmV95Fxm8lU25KuIsmjTYLGiw7BlIf9L0wqsm_IwShZQZliJZn8avXHYRVi/p.jpeg?fv_content=true&size_mode=5"  target="_blank">
          <v-list-item-icon>
            <v-icon>mdi-image</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Wireframe</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-main>
      <start></start>
    </v-main>
  </v-app>
</template>

<script>
import Start from "@/components/Start";

export default {
  name: 'App',

  components: {
    Start,
  },

  data: () => ({
    //
  }),
};
</script>
