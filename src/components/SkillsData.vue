<script setup>
defineProps({
  skillsName: String,
  percentage: String,
});
</script>

<template>
  <div class="skills_data">
    <div class="skills_titles">
      <h3 class="skills_name">{{ skillsName }}</h3>
      <span class="skills_number">{{ percentage }}</span>
    </div>
    <div class="skills_bar">
      <span class="skillPercentage"></span>
    </div>
  </div>
</template>

<style scoped>
.skills_titles {
  display: flex;
  justify-content: space-between;
  padding-bottom: 10px;
}

.skills_data {
  margin-bottom: 0.5em;
}
.skills_number {
  display: flex;
  align-items: flex-end;
}
.skills_number,
.skills_name {
  font-size: 1em;
  font-weight: 200;
}

.skills_bar,
.skillPercentage {
  height: 5px;
  border-radius: 0.25rem;
}

.skills_bar {
  background-color: hsl(20, 92%, 85%);
}

.skillPercentage {
  display: block;
  background-color: hsl(20, 69%, 61%);
  width: v-bind("percentage");
}
/* .skills_javascript {
  width: 60%;
}
.skills_css {
  width: 50%;
}
.skills_html {
  width: 50%;
}
.skills_node {
  width: 40%;
}
.skills_esnext {
  width: 10%;
}
.skills_ajax {
  width: 10%;
}
.skills_bootstrap {
  width: 10%;
}
.skills_vuejs {
  width: 10%;
}
.skills_jquery {
  width: 10%;
}
.skills_angular {
  width: 10%;
} */
</style>
