<template>
    <v-row>
      <v-col cols="12" sm="3" v-for="(Product, i) in Products" :key="i">
          <v-card class="mx-auto" max-width="344">
              <v-img :src="Product.img" height="200px" cover></v-img>
              <v-card-title>{{ Product.type }}</v-card-title>
              <v-card-subtitle>Meskie Buty treningows</v-card-subtitle>
              <v-card-title>{{ Product.money}}</v-card-title>
              <v-divider></v-divider>
              <v-card-actions>
                <v-btn variant="text">3 Kolory</v-btn>
                <v-spacer></v-spacer>
                <v-btn class="orange-lighten-2" icon="mdi-chevron-down"></v-btn>
              </v-card-actions>
          </v-card>
      </v-col>
    </v-row>
  </template>
  
  <script>
  export default {
    data() {
      return {
        Products: [
          {
            img:'/src/img/1.nike.png',
            type:'nike shose',
            money:'380$'
          },
          {
            img:'/src/img/2.nike.png',
            type:'nike air shose',
            money:'290$'
          },
          {
            img:'/src/img/3.nike.jpg',
            type:'adidas one',
            money:'180$'
          },
          {
            img:'/src/img/4.nike.jpg',
            type:'air adidas',
            money:'355$'
          },
          {
            img:'/src/img/5.nike.png',
            type:'puma one',
            money:'349$'
          },
          {
            img:'/src/img/6.nike.png',
            type:'puma air',
            money:'347$'
          },
          {
            img:'/src/img/7.nike.png',
            type:'adidas',
            money:'234$'
          },
          {
            img:'/src/img/8.nike.png',
            type:'nike',
            money:'678$'
          },
        ]
      }
    }
  }
  </script>
  
  <style>
  
  </style>
  