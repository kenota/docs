<template>
  <div class="text-xs-center">
    <v-menu transition="v-fade-transition">
      <v-btn dark primary slot="activator">Fade Transition</v-btn>
      <v-list>
        <v-list-tile v-for="n in 5" :key="n">
          <v-list-tile-title v-text="'Item ' + n"></v-list-tile-title>
        </v-list-tile>
      </v-list>
    </v-menu>
  </div>
</template>
