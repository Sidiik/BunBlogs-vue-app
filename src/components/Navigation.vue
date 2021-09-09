<template>
  <div class="container">
    <div class="branding">
      <router-link class="link main-link" :to="{ name: 'Home' }">
        BunBlogs</router-link
      >
    </div>
    <div class="nav-links">
      <router-link class="link" :to="{ name: 'Home' }">Home</router-link>
      <router-link class="link" to="{ name: '#' }">Blogs</router-link>
      <router-link class="link" to="{ name: '#' }">Create Blog</router-link>
      <router-link class="link" to="{ name: '#' }">Register/Login</router-link>
      <router-link class="link" :to="{ name: 'About' }">About</router-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
  z-index: 999;
  padding: 0.5rem 1rem;
}
.main-link {
  font-size: 2rem;
}

.link {
  text-decoration: none;
  margin-left: 1rem;
  color: black;
  user-select: none;
  font-weight: 600;
}
.link:hover {
  color: #1c80c4;
  transition: all 0.3s ease-in;
}
</style>
