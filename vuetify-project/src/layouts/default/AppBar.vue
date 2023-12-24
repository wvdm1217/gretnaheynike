<template>
  <v-app-bar flat v-if="route.path !== '/'">
    <v-app-bar-title>
      <nav-button href="/" icon="mdi-home" text="Gretna Heynike" />
    </v-app-bar-title>
  </v-app-bar>
</template>

<script lang="ts" setup>
import { useRoute } from 'vue-router';
import NavButton from '@/components/NavButton.vue';

const route = useRoute();
</script>
