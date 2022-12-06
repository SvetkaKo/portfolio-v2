<script>
import { RouterLink } from 'vue-router';

export default {
  name: 'Navigation',
  methods: {},
};
</script>

<template>
  <div class="nav slide sticky">
    <div class="nav__box">
      <div class="logo-box">
        <RouterLink class="logo" to="/"><h3>SK</h3></RouterLink>
      </div>

      <nav class="nav__nav">
        <ul class="nav__list">
          <li class="nav__list-item">
            <RouterLink class="nav__list-link" to="/">Home</RouterLink>
          </li>
          <li class="nav__list-item">
            <RouterLink class="nav__list-link" to="/about">About</RouterLink>
          </li>
          <li class="nav__list-item">
            <RouterLink class="nav__list-link" to="/portfolio">Portfolio</RouterLink>
          </li>
          <li class="nav__list-item">
            <RouterLink class="nav__list-link" to="/contact">Contact</RouterLink>
          </li>
        </ul>
        <a class="btn nav__btn" href="" target="_blank">Resume</a>

        <!-- <ul class="web">
          <li class="web-item">
            <a href="mailto:skovakina@gmail.com" class="web-link" target="_blank">
              <svg class="web-icon"><use xlink:href="src/images/sprite.svg#icon-envelop"></use></svg>
            </a>
          </li>

          <li class="web-item">
            <a href="https://www.linkedin.com/in/svetlana-kovakina-b196731b6/" class="web-link" target="_blank">
              <svg class="web-icon"><use xlink:href="src/images/sprite.svg#icon-linkedin2"></use></svg>
            </a>
          </li>
        </ul> -->
      </nav>
    </div>
  </div>
</template>
