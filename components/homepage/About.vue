<template>
  <section
    id="about"
    class="about container hp-grid"
    data-aos="fade-up"
    data-aos-offset="200"
    tabindex="-1"
  >
    <h2>About</h2>
    <div>
      <p>
        Hey, I’m Jeremy! I’m a front-end developer and designer who loves
        solving problems and building awesome things for the web, and at my
        core, I’m a learner. Whenever I see something cool or engaging I
        immediately need to know how it's done so that I can incorporate it into
        my own work, and that’s led to me learning a little bit about a lot of
        different things.
      </p>
      <p>
        I graduated from the
        <a href="https://scad.edu" target="_blank" rel="noopener"
          >Savannah College of Art and Design</a
        >
        with my bachelor’s and have been working in the web development field
        ever since. When I'm not coding you can typically find me gaming,
        writing the Next Great American Novel™, or trying to prevent my
        illustration skills from atrophying.
      </p>
      <div class="skills-lists">
        <div>
          <strong class="skills-lists__title"
            >UI <span class="accent">+</span> Design</strong
          >
          <ul class="skills-lists__list">
            <li v-for="skill in skills.design" :key="skill">
              {{ skill }}
            </li>
          </ul>
        </div>
        <div>
          <strong class="skills-lists__title">Development</strong>
          <ul class="skills-lists__list">
            <li v-for="skill in skills.development" :key="skill">
              {{ skill }}
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      skills: {
        design: [
          'Wireframing',
          'UI Design',
          'Figma',
          'Sketch App',
          'Photoshop',
          'Illustrator',
          'Logo Design',
        ],
        development: [
          'Javascript (ES6+)',
          'Typescript',
          'React / NextJS',
          'Remix',
          'GraphQL',
          'Shopify Plus / Hydrogen',
          'Headless eCommerce',
          'MaterialUI',
          'HTML / HTML5',
          'CSS3 / SASS / BEM',
          'Version Control (Git)',
          'WordPress / PHP / Twig / ACF',
          'Responsive / Mobile First',
          'Performance / Accessibility',
        ],
      },
    }
  },
}
</script>
