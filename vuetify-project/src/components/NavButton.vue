<template>
    <v-col cols="auto">
        <v-btn :href="href" min-width="164" rel="noopener noreferrer" variant="text">
            <v-icon :icon="icon" size="large" start />

            {{ text }}
        </v-btn>
    </v-col>
</template>
  
<script>
export default {
    props: {
        href: String,
        icon: String,
        text: String,
    },
};
</script>