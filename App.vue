<template>
  <div id="app">
    <BlogComponent />
    <blogsDetails />
    <ProjectComponent />

  </div>
</template>

<script>

import blogsDetails from './components/blogsDetails.vue';
import BlogComponent from './components/BlogComponent.vue';
import ProjectComponent from './components/ProjectComponent.vue';

export default {
  name: 'App',
  components: {
    BlogComponent,
    blogsDetails,
    ProjectComponent
  }
}
</script>

<style scoped></style>
