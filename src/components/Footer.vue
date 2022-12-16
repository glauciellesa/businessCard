<script setup>
import { ref } from "vue";
</script>

<template>
  <div class="footer">
    <a href="https://www.linkedin.com/in/glauciellec/">
      <i class="fa-brands fa-linkedin"></i>
    </a>
    <a href="https://www.instagram.com/eidizai_portugues/">
      <i class="fa-brands fa-square-instagram"></i>
    </a>
    <a href="https://github.com/glauciellesa">
      <i class="fa-brands fa-square-github"></i>
    </a>
  </div>
</template>

<style scoped>
.footer {
  display: flex;
  justify-content: center;
  padding: 10px;
  background-color: #161619;
  gap: 10px;
}
a {
  color: #d2d2d2;
  font-size: 20px;
}
</style>
