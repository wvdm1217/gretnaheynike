<template>
  <v-container class="fill-height">
    <v-responsive class="align-center text-center fill-height">


      <h1 class="text-h1 font-weight-bold">GRETNA HEYNIKE</h1>

      <div class="text-body-6 font-weight-bold mb-n1 mt-1">Violinist | Musical Educator | Professional Musician</div>

      <div class="py-14" />

      <v-row class="d-flex align-center justify-center">
        <v-col cols="auto">
          <v-btn
            href="/about"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon
              icon="mdi-music-note-eighth"
              size="large"
              start
            />

            About
          </v-btn>
        </v-col>

        <v-col cols="auto">
          <v-btn
            href="/teaching"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon
              icon="mdi-music-note-quarter"
              size="large"
              start
            />

            Teaching
          </v-btn>
        </v-col>

        <v-col cols="auto">
          <v-btn
            href="/performance"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon
              icon="mdi-music-note-half"
              size="large"
              start
            />

            Performance
          </v-btn>
        </v-col>

        <v-col cols="auto">
          <v-btn
            href="/contact"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon
              icon="mdi-music-note"
              size="large"
              start
            />

            Contact
          </v-btn>
        </v-col>
      </v-row>
    </v-responsive>
  </v-container>
</template>

<script lang="ts" setup>
  //
</script>
