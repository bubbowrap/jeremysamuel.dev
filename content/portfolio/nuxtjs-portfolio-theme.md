---
title: NuxtJS Portfolio Theme
description: Personal website portfolio built with NuxtJS.
category: Design, Development
role: Design, Front-end Development, Back-end Development
link: https://jeremysamuel.dev
github: https://github.com/bubbowrap/jeremysamuel.dev
thumbnail: nuxt-theme/nuxt-theme-thumb.jpg
slides: ['nuxt-theme/nuxt-theme-mobile-ss.jpg', 'nuxt-theme/nuxt-theme-hp.jpg']
alt: NuxtJS Portfolio Theme Screenshot
client: Personal Project
tools: Sketch, VSCode
tags: NuxtJS, SCSS, Markdown, Netlify
order: 0
active: true
---

## Project Details

The last iteration of my portfolio site lived on Wordpress and was built with Timber/Twig/ACF, and while that worked out perfectly for my needs, it was also a bit bloated with unneccesary Wordpress junk and still used jQuery to do a few things, knocking down my Lighthouse scores and making the site load a little bit slower. I could've lived with all of that, but _then_ my long-time webhost almost doubled their prices without so much as an e-mail and autorenewed my plan and well...needless to say, I wasn't very happy about that. It gave me _just_ enough righteous anger and motivation to completely rebuild my portfolio as a much more secure static site with Nuxt!

The main tools used in this site were:

- **Sketch** to design the UI/UX.
- **NuxtJS** to manage the pages/routes, along with **SASS** to build out the design from scratch.
- **Markdown** to maintain content.
- **Netlify** for hosting and CI/CD deployments.

I considered integrating a CMS, however since I was the only one who'd be updating the site and even _then_ only every few months or so, I ultimately decided to just use markdown files to make any changes that I needed. I personally think this helped a lot with my Lighthouse scores (Straight 100s at the time of writing this, baby!).

I deployed the site with **Netlify**, which means that I'm paying 0 dollars per year to host my now much lighter site rather than the 200ish I was hit with in 2020. In some ways I'm glad that it happened because Nuxt is a lot of fun and I'm really looking forward to building out more things with it in the future!
