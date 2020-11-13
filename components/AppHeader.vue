<template>
  <v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="white"
      elevate-on-scroll
      rounded
      scroll-target="#scrolling-techniques-7"
    >
      <template v-slot:extension>
        <v-tabs align-with-title>
          <v-tab>HOME</v-tab>
          <v-tab>ABOUT</v-tab>
          <v-tab>EXPERIENCE</v-tab>
          <v-tab>SKILLS</v-tab>
        </v-tabs>
      </template>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-7"
      class="overflow-y-auto"
      max-height="600"
    >
      <v-container style="height: 1500px;">
      </v-container>
    </v-sheet>
  </v-card>
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'

const HEADER_TITLE = "Welcome to Tomohiro Yoshida's Portfolio"

export default defineComponent({
	name: 'AppHeader',
  setup(){
		return {
			HEADER_TITLE
		}
	}
})
</script>

<style scoped></style>