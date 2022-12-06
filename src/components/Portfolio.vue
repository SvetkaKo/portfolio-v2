<script>
import ProjectsVue from './Projects.vue';
export default {
  name: 'Portfolio',
  methods: {},
};
</script>

<template>
  <!-- portfolio page - header-->
  <div class="container cont__header">
    <div class="header">
      <div class="header__text-box">
        <h4 class="header__h4">Welcome to my</h4>
        <h1 class="header__h1">portfolio</h1>
        <h3 class="header__h4">Check out some of my latest UI/UX design case studies</h3>
        <p class="paragraph header__p">
          I've been practicing with various technologies and tools, working on a range of different projects, including web applications and UX design
          explorations.
        </p>
      </div>
      <img class="header__hero" src="" alt="hero" />
    </div>
  </div>
  <ProjectsVue />
</template>
