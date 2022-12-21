<template>
  <div>
    <v-toolbar
      dark
      flat
      image="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-toolbar-title>Bitcoin</v-toolbar-title>
      <v-toolbar-items>
        <DropDown />
        <v-btn flat>
          <span>Sign out</span>
        </v-btn>
        <v-btn flat>
          <span>Sign out</span>
        </v-btn>
        <v-btn flat>
          <span>Sign out</span>
        </v-btn>
      </v-toolbar-items>
      <v-spacer></v-spacer>
    </v-toolbar>
  </div>
</template>

<script>
import DropDown from "./DropDown.vue";
export default {
  components: {
    DropDown,
  },
};
</script>

<style></style>
