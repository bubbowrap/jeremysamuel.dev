<template>
  <section class="homepage-hero container">
    <h1
      class="homepage-hero__title aos-init"
      data-aos="fade-up"
      data-aos-offset="200"
      data-aos-delay="100"
    >
      Hi, I’m <strong class="accent">Jeremy Samuel</strong>, and I’m a front-end
      developer. I design <span class="accent">+</span> code experiences for the
      web and mobile devices.
    </h1>
    <a
      :href="`mailto:${$store.state.emailAddress}`"
      class="btn btn--line aos-init"
      data-aos="fade-up"
      data-aos-once="true"
      data-aos-delay="150"
      >Contact Me</a
    >

    <ul
      class="homepage-hero__social aos-init"
      data-aos="fade-up"
      data-aos-delay="200"
    >
      <li class="homepage-hero__social-item">
        <a
          href="https://www.codepen.io/bubbowrap"
          class="homepage-hero__social-link tooltip"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="See my work on Codepen"
        >
          <span class="tooltiptext">My Codepen</span>
          <svg viewBox="0 0 24 24">
            <path
              fill="#E6052A"
              d="M15.09,12L12,14.08V14.09L8.91,12L12,9.92V9.92L15.09,12M12,2C11.84,2 11.68,2.06 11.53,2.15L2.5,8.11C2.27,8.22 2.09,8.43 2,8.67V14.92C2,15.33 2,15.33 2.15,15.53L11.53,21.86C11.67,21.96 11.84,22 12,22C12.16,22 12.33,21.95 12.47,21.85L21.85,15.5C22,15.33 22,15.33 22,14.92V8.67C21.91,8.42 21.73,8.22 21.5,8.1L12.47,2.15C12.32,2.05 12.16,2 12,2M16.58,13L19.59,15.04L12.83,19.6V15.53L16.58,13M19.69,8.9L16.58,11L12.83,8.47V4.38L19.69,8.9M20.33,10.47V13.53L18.07,12L20.33,10.47M7.42,13L11.17,15.54V19.6L4.41,15.04L7.42,13M4.31,8.9L11.17,4.39V8.5L7.42,11L4.31,8.9M3.67,10.5L5.93,12L3.67,13.54V10.5Z"
            ></path>
          </svg>
        </a>
      </li>
      <li class="homepage-hero__social-item">
        <a
          href="https://www.github.com/bubbowrap"
          class="homepage-hero__social-link tooltip"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="See my work on Github"
        >
          <span class="tooltiptext">My Github</span>
          <svg viewBox="0 0 24 24">
            <path
              fill="#E6052A"
              d="M20.38,8.53C20.54,8.13 21.06,6.54 20.21,4.39C20.21,4.39 18.9,4 15.91,6C14.66,5.67 13.33,5.62 12,5.62C10.68,5.62 9.34,5.67 8.09,6C5.1,3.97 3.79,4.39 3.79,4.39C2.94,6.54 3.46,8.13 3.63,8.53C2.61,9.62 2,11 2,12.72C2,19.16 6.16,20.61 12,20.61C17.79,20.61 22,19.16 22,12.72C22,11 21.39,9.62 20.38,8.53M12,19.38C7.88,19.38 4.53,19.19 4.53,15.19C4.53,14.24 5,13.34 5.8,12.61C7.14,11.38 9.43,12.03 12,12.03C14.59,12.03 16.85,11.38 18.2,12.61C19,13.34 19.5,14.23 19.5,15.19C19.5,19.18 16.13,19.38 12,19.38M8.86,13.12C8.04,13.12 7.36,14.12 7.36,15.34C7.36,16.57 8.04,17.58 8.86,17.58C9.69,17.58 10.36,16.58 10.36,15.34C10.36,14.11 9.69,13.12 8.86,13.12M15.14,13.12C14.31,13.12 13.64,14.11 13.64,15.34C13.64,16.58 14.31,17.58 15.14,17.58C15.96,17.58 16.64,16.58 16.64,15.34C16.64,14.11 16,13.12 15.14,13.12Z"
            ></path>
          </svg>
        </a>
      </li>
      <li class="homepage-hero__social-item">
        <a
          href="https://www.linkedin.com/in/bubbowrap"
          class="homepage-hero__social-link tooltip"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Connect with me on LinkedIn"
        >
          <span class="tooltiptext">My LinkedIn</span>
          <svg viewBox="0 0 24 24">
            <path
              fill="#E6052A"
              d="M21,21H17V14.25C17,13.19 15.81,12.31 14.75,12.31C13.69,12.31 13,13.19 13,14.25V21H9V9H13V11C13.66,9.93 15.36,9.24 16.5,9.24C19,9.24 21,11.28 21,13.75V21M7,21H3V9H7V21M5,3A2,2 0 0,1 7,5A2,2 0 0,1 5,7A2,2 0 0,1 3,5A2,2 0 0,1 5,3Z"
            ></path>
          </svg>
        </a>
      </li>
    </ul>
  </section>
</template>
