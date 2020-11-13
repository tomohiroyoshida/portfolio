<template>
  <v-app>
    <v-container fluid>
      <v-row no-gutters>
        <v-col cols="12">
          <AppHeader />
          <v-sheet
            id="scrolling-techniques-7"
            class="overflow-y-auto"
            max-height="600"
          >
            <v-container style="height: 1500px;">
            </v-container>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'
export default defineComponent({
  name: 'home',
  setup(){}
})
</script>

<style scoped></style>