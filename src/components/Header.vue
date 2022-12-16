<script setup>
defineProps({
  name: String,
  title: String,
});
</script>

<template>
  <div class="divImg">
    <a href="https://github.com/glauciellesa" target="_blank">
      <img
        src="https://avatars.githubusercontent.com/u/65506911?v=4"
        alt="Glau Img"
      />
    </a>
  </div>
  <h1 class="name">{{ name }}</h1>
  <p class="title">{{ title }}</p>
  <div class="buttons">
    <button class="email" type="button">
      <i class="far fa-envelope"></i>
      Email
    </button>
    <a href="https://www.linkedin.com/in/glauciellec/">
      <button class="linkedin" type="button">
        <i class="fa-brands fa-linkedin"></i>
        LinkedIn
      </button>
    </a>
  </div>
</template>

<style scoped>
.divImg {
  margin-top: 0;
}

img {
  width: 20em;
  border-radius: 5px 5px 0 0;
}
.name {
  padding-top: 20px;
}

.title {
  color: #f3bf99;
}

.buttons {
  display: flex;
  justify-content: center;
  gap: 10px;
}

.linkedin {
  background-color: #5093e2;
  color: #fff;
}
.GlauImg:hover {
  filter: drop-shadow(0 0 2em #9e9e9eaa);
}
</style>
