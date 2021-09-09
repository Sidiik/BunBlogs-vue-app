<template>
  <BlogPost :post="welcomeScreen" />
</template>

<script>
import BlogPost from "../components/BlogPost.vue";
export default {
  name: "Home",
  components: {
    BlogPost,
  },
  data() {
    return {
      welcomeScreen: {
        title: "Hey this is title screen",
        welcomeScreen: true,
        blog:
          " Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate,placeat. Ipsa corporis fuga quos quae dignissimos cumque. Vitae eni cupiditate excepturi sed ex facere voluptatibus eum cum ab.",
      },
    };
  },
};
</script>

<style></style>
