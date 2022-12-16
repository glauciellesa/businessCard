<template>
  <div class="body">
    <h3>About</h3>
    <p>
      I'm JavaScript, HTML and CSS apprentice based out of Brussels, Belgium.
      I'm passionate about technology and self-taught.
    </p>
    <h3>Skills</h3>
    <div>
      <h4 class="subtitle">Frontend developer</h4>
      <span class="skills_subtitle">1 years of experience</span>
    </div>
    <div class="skills_list">
      <div class="skills_data">
        <div class="skills_titles">
          <h3 class="skills_name">JavaScript</h3>
          <span class="skills_number">60%</span>
        </div>
        <div class="skills_bar">
          <span class="skills_percentage skills_javascript"></span>
        </div>
      </div>

      <div class="skills_data">
        <div class="skills_titles">
          <h3 class="skills_name">CSS</h3>
          <span class="skills_number">50%</span>
        </div>
        <div class="skills_bar">
          <span class="skills_percentage skills_css"></span>
        </div>
      </div>

      <div class="skills_data">
        <div class="skills_titles">
          <h3 class="skills_name">HTML</h3>
          <span class="skills_number">50%</span>
        </div>
        <div class="skills_bar">
          <span class="skills_percentage skills_html"></span>
        </div>
      </div>

      <div class="skills_data">
        <div class="skills_titles">
          <h3 class="skills_name">Node</h3>
          <span class="skills_number">40%</span>
        </div>
        <div class="skills_bar">
          <span class="skills_percentage skills_node"></span>
        </div>
      </div>
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
.subtitle {
  margin: 10px 05px;
}
.skills_subtitle {
  font-size: 0.8em;
  font-weight: 100;
  color: #d2d2d2;
  margin: 5px;
}
.skills_titles {
  display: flex;
  justify-content: space-between;
  padding-bottom: 10px;
}
.skills_list {
  padding: 1rem;
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
.skills_percentage {
  height: 5px;
  border-radius: 0.25rem;
}

.skills_bar {
  background-color: hsl(20, 92%, 85%);
}

.skills_percentage {
  display: block;
  background-color: hsl(20, 69%, 61%);
}
.skills_javascript {
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
}
</style>
