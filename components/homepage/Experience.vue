<template>
  <section
    id="experience"
    class="experience container hp-grid"
    data-aos="fade-up"
    data-aos-offset="200"
    tabindex="-1"
  >
    <h2>Experience</h2>
    <div class="experience-box">
      <div class="experience-box__header">
        <div>
          <h3 class="experience-box__title">Front-end Developer</h3>
          <h4 class="experience-box__company">Defyned Brands</h4>
        </div>
        <div class="experience-box__date">March 2022 - August 2024</div>
      </div>
      <ul class="experience-box__list">
        <li class="experience-box__list-tem">
          Designed, built, and maintained ReactJS components for customizing
          content and displaying customer data on headless eCommerce Shopify
          sites (Hydrogen/GraphQL).
        </li>
        <li class="experience-box__list-tem">
          Collaborated across data and marketing teams to implement new
          features, third party plugins, and applications.
        </li>
        <li class="experience-box__list-tem">
          Continuously improved code quality, design, accessibility, and
          performance across websites.
        </li>
      </ul>
    </div>
    <div class="experience-box">
      <div class="experience-box__header">
        <div>
          <h3 class="experience-box__title">Senior Front-end Developer</h3>
          <h4 class="experience-box__company">Launch That</h4>
        </div>
        <div class="experience-box__date">April 2017 - March 2022</div>
      </div>
      <ul class="experience-box__list">
        <li class="experience-box__list-tem">
          Designed and built interactive tools with React, Javascript (ES5/ES6),
          PHP, Twig, ACF, HTML, and SASS.
        </li>
        <li class="experience-box__list-tem">
          Led development of new websites and high-converting landing pages,
          ads, and calls to action with a focus on performance and
          accessibility.
        </li>
        <li>
          Collaborated with writers, marketers, and other developers to produce
          new tools, components, and templates focused on improving the user
          experience and increasing conversions.
        </li>
      </ul>
    </div>
    <div class="experience-box">
      <div class="experience-box__header">
        <div>
          <h3 class="experience-box__title">Web Designer</h3>
          <h4 class="experience-box__company">NetSource Technologies</h4>
        </div>
        <div class="experience-box__date">November 2012 - March 2017</div>
      </div>
      <ul class="experience-box__list">
        <li class="experience-box__list-tem">
          Collaborated with sales team, programmers, and clients through all
          steps of the website creation process from UI/UX to website launch.
        </li>
        <li class="experience-box__list-tem">
          Advised clients on identity and strategy; worked to understand client
          end goals and needs while also being an advocate for the end user.
        </li>
        <li class="experience-box__list-tem">
          Established and maintained rapport with clients and team members.
        </li>
      </ul>
    </div>
    <div class="experience-box">
      <div class="experience-box__header">
        <div>
          <h3 class="experience-box__title">Production Intern</h3>
          <h4 class="experience-box__company">WCJB TV20</h4>
        </div>
        <div class="experience-box__date">March 2009 - April 2009</div>
      </div>
      <ul class="experience-box__list">
        <li class="experience-box__list-tem">
          Edited video footage for use in television commercials, designed and
          animated motion graphics for advertisements / commercials.
        </li>
        <li class="experience-box__list-tem">
          Worked with supervisors and clients to produce appealing
          advertisements.
        </li>
      </ul>
    </div>
    <div class="experience-resume-btn">
      <a
        :href="$store.state.resumeLink"
        class="btn btn--line"
        target="_blank"
        rel="noopener"
        >View Resume</a
      >
    </div>
  </section>
</template>
