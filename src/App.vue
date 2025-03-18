<template>
  <v-app>
    <v-app-bar>
      <v-app-bar-title>Vue + Three.js + Vuetify</v-app-bar-title>
    </v-app-bar>

    <v-main>
      <v-container fluid class="pa-0 fill-height">
        <div ref="containerRef" class="three-container" />
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import { useThree } from "./composables/useThree";

const { containerRef } = useThree();
</script>

<style scoped>
.three-container {
  width: 100%;
  height: 100%;
}
</style>
