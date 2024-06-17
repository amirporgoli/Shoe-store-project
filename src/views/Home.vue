<template>
  <v-app>
    <v_main>
      <v-container>
        <v-row>
          <v-col cols="4" sm="2">
            <v-card width="100%" color="#f5f5f5" flat class="pa-2">
              <h4>PRODUCTY: 198</h4>
              <span>FILTRUJ WG</span>
              <v-select
                clearable
                label="select"
                :items="Items"
                variant="outlined"
                class="mt-2"
              ></v-select>
              <v-divider></v-divider>
              <Item />
              <div class="d-flex justify-space-around my-2">
                <v-color-picker
                  v-model="C2"
                  hide-inputs
                  hide-canvas
                  hide-sliders
                  show-swatches
                ></v-color-picker>
              </div>
            </v-card>
          </v-col>
          <v-col cols="8" sm="10">
            <v-breadcrumbs :items="Ittems">
              <template v-slot:divider>
                <v-icon icon="mdi-chevron-right"></v-icon>
              </template>
            </v-breadcrumbs>
            <v-divider></v-divider>
            <v-toolbar color="transparent" class="pa-4">
              <h1>BUTY MESKIE</h1>
              <v-spacer></v-spacer>
              <v-select clearable label="select" :items="['california','texas','ostrich','husen','florida']"></v-select>
            </v-toolbar>
            <products />
            <v-card variant="outlined" class="my-2">
              <v-row>
                <v-col class="text-center" cols="2" sm="2">
                  <v-btn append-icon=" mdi-chevron-right" flat></v-btn>
                </v-col>
                <v-col cols="8" sm="8" class="text-center pt-5">
                  <span class="text-red">Kolejne 50 prodktow 50 z198</span>
                </v-col>
                <v-col cols="2" sm="2" class="text-center">
                  <v-btn prepend-icon=" mdi-chevron-left" flat></v-btn>
                </v-col>
              </v-row>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v_main>
  </v-app>
</template>

<script>
import Item from "@/components/Item.vue";
import Products from '@/components/products.vue';
export default {
  data() {
    return {
      Items: ["nike", "adidas", "puma", "ostrich"],
      Ittems: [
        {
          title: "Strona goina",
          disabled: false,
          href: "breadcrumbs_dashboard",
        },
        {
          title: "Buty",
          disabled: false,
          href: "breadcrumbs_link_1",
        },
        {
          title: "Mesky",
          disabled: true,
          href: "breadcrumbs_link_2",
        },
      ],
    };
  },
  components: { Item, Products },
};
</script>
