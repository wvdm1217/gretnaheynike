<script setup lang="ts">
defineProps<{
    href: string,
    icon: string,
    text: string
}>()
</script>

<template>
    <v-col cols="auto">
        <v-btn :href="href" min-width="164" rel="noopener noreferrer" variant="text">
            <v-icon :icon="icon" size="large" start />

            {{ text }}
        </v-btn>
    </v-col>
</template>
  
