<template>
  <div class="footer">
    <div class="right">
      <h1>BunBlogs</h1>
      <div class="icons">
        <div>
          <i class="fab fa-facebook"></i>
        </div>
        <div>
          <i class="fab fa-youtube"></i>
        </div>
      </div>
    </div>
    <div class="center">
      <h2>Home</h2>
      <h2>Blogs</h2>
      <h2>Login/Register</h2>
    </div>
    <div class="left">
      Copyright 2021 &copy; sidiik
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  position: fixed;
  bottom: 0px;
  background: #2f2f2f;
  width: 100%;
  height: 25vh;
  display: flex;
  justify-content: space-around;
  align-items: center;
  color: white;
}
.right {
  display: flex;
  flex-direction: column;
}
i {
  font-size: 2rem;
}
</style>
