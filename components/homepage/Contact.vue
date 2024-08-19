<template>
  <section
    id="contact"
    class="contact container hp-grid"
    data-aos="fade-up"
    data-aos-offset="200"
    tabindex="-1"
  >
    <h2>Contact</h2>
    <div>
      <p>
        Check out my
        <a href="https://codepen.io/bubbowrap">Codepen</a> and
        <a href="https://www.github.com/bubbowrap">Github</a> to see what I’m
        working on, or send me an email if you want to chat!
      </p>
      <a :href="`mailto:${$store.state.emailAddress}`" class="btn btn--line"
        >Message Me</a
      >
    </div>
  </section>
</template>
