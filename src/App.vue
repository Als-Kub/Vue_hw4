<template>
  <MainPage />
  <BlogPage />
  <BlogDetailsPage />
</template>

<script>
import MainPage from "./components/MainPage.vue";
import BlogPage from "./components/BlogPage.vue";
import BlogDetailsPage from "./components/BlogDetailsPage.vue";

export default { components: { MainPage, BlogPage, BlogDetailsPage } };
</script>

<style lang="scss"></style>
