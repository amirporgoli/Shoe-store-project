<template>
  <v-app-bar height="80" flat>
    <v-app-bar-title>
      <h4>FOOTBALL <strong class="color">SPORT</strong>.PL</h4>
    </v-app-bar-title>
    <v-spacer></v-spacer>
    <v-btn>OPINIE O STRONIE</v-btn>
    <v-btn prepend-icon="mdi mdi-email">
      <template v-slot:prepend>
        <v-icon color=""></v-icon>
      </template>
      mrporgoli81@gmail.com
    </v-btn>
    <v-btn prepend-icon="mdi mdi-cart">
      <template v-slot:prepend>
        <v-icon></v-icon>
      </template>
      LOGOWANIE
    </v-btn>
  </v-app-bar>
  <v-app-bar height="80" color="black" flat>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      weadsrtw kategorie
    </v-btn>
    <v-avatar rounded="0" color="#ff570c" size="128px" class="pa-2 mr-16">
      <v-img src="/src/img/99.jpg" cover></v-img>
    </v-avatar>
    <v-btn class="mr-16">ASWETDFF TO SSDWRGGG FGFJKIUYTRDDERYFRTIP</v-btn>
    <v-avatar size="128px" class="pa-2 mr-16" rounded="0">
      <v-img src="/src/img/adadiss.png" cover></v-img>
    </v-avatar>
    <v-spacer></v-spacer>
    <v-text-field
      append-inner-icon="mdi-magnify"
      flat
      single-line
      hide-details
      density="compact"
      label="CEZEGO SZUKASZ?"
    ></v-text-field>
  </v-app-bar>
  <v-app-bar color="#ff570c" flat>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      BUTY
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      KOLEKCJA
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
     ODZIEZ
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      AKCCESOSSORIA
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      KOOLLEKKCCJJA
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      NNOWOOSSCL
    </v-btn>
    <v-btn append-icon="mdi mdi-chevron-down" class="mr-16">
      <template v-slot:append>
        <v-icon></v-icon>
      </template>
      ODZZIEZ
    </v-btn>
  </v-app-bar>
</template>

<script setup>
</script>
<style>
.color {
  color: #fd4900;
}
</style>
