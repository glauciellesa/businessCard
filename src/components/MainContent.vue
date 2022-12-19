<script setup>
import SkillsData from "./SkillsData.vue";
</script>

<template>
  <div class="body">
    <h3>About</h3>
    <p>
      I'm JavaScript, HTML and CSS apprentice based out of Brussels, Belgium.
      I'm passionate about technology and self-taught.
    </p>
    <h3>Skills</h3>
    <span class="skills_experience">1 years of experience</span>

    <div class="skills_list">
      <SkillsData skillsName="JavaScript" percentage="70%"></SkillsData>
      <SkillsData skillsName="CSS" percentage="50%"></SkillsData>
      <SkillsData skillsName="HTM" percentage="60%"></SkillsData>
      <SkillsData skillsName="Node" percentage="50%"></SkillsData>
      <SkillsData skillsName="React" percentage="40%"></SkillsData>
    </div>
  </div>
</template>

<style scoped>
.body {
  color: #fff;
  text-align: left;
  padding: 20px;
}
h3 {
  padding-top: 20px;
}
p {
  font-size: 0.8em;
}
.skills_experience {
  font-size: 0.8em;
  font-weight: 100;
  color: #f3bf99;
  margin: 5px;
}
.skills_list {
  padding: 1rem;
}
</style>
