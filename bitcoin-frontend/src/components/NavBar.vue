<template>
  <v-toolbar theme="dark" flat>
    <v-toolbar-title>Bitcoin</v-toolbar-title>
    <v-toolbar-items>
      <v-btn flat>
        <span>Sign out</span>
      </v-btn>
      <v-btn flat>
        <span>Sign out</span>
      </v-btn>
      <DropDown />
      <v-btn flat>
        <span>Sign out</span>
      </v-btn>
    </v-toolbar-items>
  </v-toolbar>
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
