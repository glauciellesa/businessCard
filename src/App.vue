<script setup>
import Header from "./components/Header.vue";
import MainContent from "./components/MainContent.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="card">
    <Header name="Glaucielle Celestina de Sá" title="Frontend Developer" />
    <MainContent />
    <Footer />
  </div>
</template>

<style scoped>
.card {
  width: 20em;
  background-color: #1a1b21;
  border-radius: 1em;
  overflow: hidden;
}
</style>
