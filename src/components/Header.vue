<script setup>
import SocialButton from "./SocialButton.vue";

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
    <SocialButton
      href="mailto:glauciellec@gmail.com"
      class="mail"
      icon="far fa-envelope"
      buttonName="Email"
    />
    <SocialButton
      href="https://www.linkedin.com/in/glauciellec/"
      class="linkedin"
      icon="fa-brands fa-linkedin"
      buttonName="LinkedIn"
    />
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
  padding-top: 10px;
  display: flex;
  justify-content: center;
  gap: 10px;
}
</style>
