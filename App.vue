<template>
  <div id="app">
    <BlogComponent />
    <blogsDetails />
    <ProjectComponent />
    <ProjectDetailsComponent />


  </div>
</template>

<script>

import blogsDetails from './components/blogsDetails.vue';
import BlogComponent from './components/BlogComponent.vue';
import ProjectComponent from './components/ProjectComponent.vue';
import ProjectDetailsComponent from './components/ProjectDetailsComponent.vue';

export default {
  name: 'App',
  components: {
    BlogComponent,
    blogsDetails,
    ProjectComponent,
    ProjectDetailsComponent,

  }
}
</script>

<style scoped></style>
