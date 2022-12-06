<script>
export default {
  name: 'Projects',
  methods: {},
};
</script>

<template>
  <!-- portfolio page - recent projects-->
  <div class="container cont__portfolio">
    <!-- portfolio -->
    <div class="portfolio">
      <div class="heading">
        <h3>Some of my latest work</h3>
      </div>
      <div class="portfolio__content">
        <!-- project 1 design -->
        <div class="project">
          <img src="src/images/forkify-2.jpg" alt="img" class="project__img" />

          <div class="project__header">
            <h3 class="project__name header__h3">Career Aid</h3>
            <div class="project__status">In Progress</div>
          </div>
          <div class="project__discription">
            Project based on the latest features of Vue 3 including Composition API, Vuex, Vue Router, setting up authentication and user accounts.
          </div>
          <ul class="tech__skils">
            <li class="tech__skils-item">UX</li>
            <li class="tech__skils-item">UI</li>
            <li class="tech__skils-item">Design</li>
            <li class="tech__skils-item">Case Study</li>
          </ul>
        </div>
        <!-- project 1 -->
        <div class="project">
          <img src="src/images/forkify-2.jpg" alt="img" class="project__img" />
          <div class="project__header">
            <h3 class="project__name header__h3">Music App</h3>
          </div>
          <div class="project__discription">
            <p class="project__discription-p">
              Project based on the latest features of Vue 3 including Composition API, Vuex, Vue Router, setting up authentication and user accounts.
            </p>
          </div>
          <ul class="tech__skils">
            <li class="tech__skils-item">Vue.js</li>
            <li class="tech__skils-item">HTML/CSS</li>
            <li class="tech__skils-item">TailwindCSS</li>
          </ul>
        </div>
        <!-- project 2 -->
        <div class="project">
          <img src="src/images/forkify-2.jpg" alt="img" class="project__img" />
          <div class="project__header">
            <h3 class="project__name">Forkify</h3>
          </div>
          <div class="project__discription">
            <p class="project__discription-p">Modern application for searching for a recipe or an ingredient. Explore plenty of recipes of pizza!</p>
          </div>
          <ul class="tech__skils">
            <li class="tech__skils-item">JavaScript (ES6+)</li>
            <li class="tech__skils-item">Parcel</li>
            <li class="tech__skils-item">Babel</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
