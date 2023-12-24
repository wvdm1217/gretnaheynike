<template>
    <v-footer color="secondary" class="small-footer">
        <v-container>
            <v-row>
                <v-col class="text-center" cols="12">
                    <v-btn class="ma-2" variant="text" icon="mdi-facebook" color="primary"></v-btn>
                    <v-btn class="ma-2" variant="text" icon="mdi-instagram" color="primary"></v-btn>
                    <v-btn class="ma-2" variant="text" icon="mdi-email" color="primary"></v-btn>
                </v-col>
            </v-row>
            <v-row>
                <v-col class="text-center" cols="12">
                    <span color="primary" class="text">&copy; 2023</span>
                </v-col>
            </v-row>
        </v-container>
    </v-footer>
</template>

<script lang="ts" setup>

</script>

<style scoped>
.small-footer {
    height: 50px;
}
</style>