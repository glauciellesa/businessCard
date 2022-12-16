<script setup>
defineProps({
  href: String,
  class: String,
  icon: String,
  buttonName: String,
});
</script>

<template>
  <a :href="href">
    <button :class="class" type="button">
      <i :class="icon"></i>
      {{ buttonName }}
    </button>
  </a>
</template>

<style scoped>
.linkedin {
  background-color: #5093e2;
  color: #fff;
}
</style>
