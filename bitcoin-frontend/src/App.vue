<template>
  <v-app>
    <NavBar />
    <Parallax />
    <Footer />
  </v-app>
</template>

<script setup>
import Parallax from "./components/Parallax.vue";
import Footer from "./components/Footer.vue";
import NavBar from "./components/NavBar.vue";
import { ref } from "vue";

const theme = ref("light");

function onClick() {
  theme.value = theme.value === "light" ? "dark" : "light";
}
</script>
