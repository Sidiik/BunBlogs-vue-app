<template>
  <div class="wrapper">
    <h2 v-if="post.welcomeScreen">
      {{ post.title }}
    </h2>
    <p>{{ post.blog }}</p>
  </div>
</template>

<script>
export default {
  name: "BlogPost",
  props: ["post"],
};
</script>

<style></style>
