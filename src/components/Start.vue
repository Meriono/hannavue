<template>
  <v-container>
    <v-card height="70vh" width="170vh" dark color="#2A2A2A">
      <v-row>
        <v-col cols="4">
          <h1 align="center" class="pink--text">NAMN</h1>
          <v-card
              class="overflow-y-auto"
              flat
              max-height="60vh"
              color="transparent"
          >
            <v-card-text>
              <p class="pl-4 text--lighten-4 pink--text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Nibh sed pulvinar proin gravida. Risus nullam eget felis eget. Ultricies lacus sed turpis tincidunt id aliquet risus feugiat in.</p>
              <p class="pl-4 text--lighten-3 pink--text">Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Ac turpis egestas maecenas pharetra convallis posuere morbi leo urna. Est lorem ipsum dolor sit amet consectetur. Dui vivamus arcu felis bibendum ut tristique et. Fermentum odio eu feugiat pretium nibh ipsum consequat nisl.</p>
              <p class="pl-4 text--lighten-4 pink--text">Odio ut enim blandit volutpat maecenas. Hac habitasse platea dictumst quisque sagittis purus sit. Vestibulum rhoncus est pellentesque elit ullamcorper dignissim cras tincidunt. Posuere urna nec tincidunt praesent semper feugiat nibh. Sociis natoque penatibus et magnis dis.</p>
              <p class="pl-4 text--lighten-3 pink--text">Dolor morbi non arcu risus quis varius. Eget mi proin sed libero enim sed faucibus turpis. Id faucibus nisl tincidunt eget nullam non. Nunc sed velit dignissim sodales ut eu sem integer vitae.</p>
            </v-card-text>
          </v-card>

        </v-col>
        <v-col cols="8">
          <v-card height="100%" max-height="66.5vh" width="98%" color="grey" flat>
            <v-row>
              <v-col class="px-8 pt-4">
                <v-img class="rounded"
                    :src="`https://picsum.photos/700/460?image=${3 * 5 + 10}`"
                >
                </v-img>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-card>



    <v-card height="10vh" width="170vh" color="#D1C2BF" class="my-5">

      <v-row>
          <v-card
              class="overflow-y-auto my-2"
              flat
              max-width="154vh"
              max-height="8vh"
              color="transparent"
          >
            <v-card-text>
              <p class="text--black">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Nibh sed pulvinar proin gravida. Risus nullam eget felis eget. Ultricies lacus sed turpis tincidunt id aliquet risus feugiat in. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Ac turpis egestas maecenas pharetra convallis posuere morbi leo urna. Est lorem ipsum dolor sit amet consectetur. Dui vivamus arcu felis bibendum ut tristique et. Fermentum odio eu feugiat pretium nibh ipsum consequat nisl.</p>
            </v-card-text>
          </v-card>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "Start",

  data() {
    return {
      loading: false,
      selection: 1,
      products: []
    }
  },

  methods: {
    namn() {
      this.random = "Oj nu ändrade vi" + this.nummer
      this.nummer++
    },
    addproduct() {
      this.products.push({
        namn:"En produkt",
        kostnad: 299,
        typ: "sko"
      })
    }
  }
}
</script>

<style scoped>
::-webkit-scrollbar {
  width: 3px;
}

::-webkit-scrollbar-track {
  -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
  border-radius: 10px;
}

::-webkit-scrollbar-thumb {
  border-radius: 10px;
  -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.5);
}
</style>