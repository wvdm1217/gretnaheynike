<template>
  <v-container class="fill-height">
    <v-responsive class="align-center text-center fill-height">


      <h1 class="text-h1 font-weight-bold">GRETNA HEYNIKE</h1>

      <div class="text-body-6 font-weight-bold mb-n1 mt-1">Violinist | Musical Educator | Professional Musician</div>

      <div class="py-14" />

      <v-row class="d-flex align-center justify-center">

        <NavButton href="/about" icon="mdi-music-note-sixteenth" text="About" />
        <NavButton href="/teaching" icon="mdi-music-note-eighth" text="Teaching" />
        <NavButton href="/performance" icon="mdi-music-note-quarter" text="Performance" />
        <NavButton href="/contact" icon="mdi-music-note-half" text="Contact" />
      </v-row>
    </v-responsive>
  </v-container>
</template>

<script lang="ts" setup>
//
import NavButton from '@/components/NavButton.vue';
</script>
