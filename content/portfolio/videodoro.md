---
title: Videodoro
description: A Vue pomodoro timer with a little something extra.
category: Design, Development
role: Design, Front-end Development, Back-end Development
link: https://videodoro.netlify.app/
github: https://github.com/bubbowrap/Videodoro
thumbnail: videodoro/videodoro-thumb.jpg
slides:
  [
    'videodoro/videodoro-mobile-ss.jpg',
    'videodoro/videodoro-start-dark.jpg',
    'videodoro/videodoro-video-play.jpg',
    'videodoro/videodoro-settings.jpg',
    'videodoro/videodoro-start-light.jpg',
  ]
alt: Videodoro Screenshot
client: Personal Project
tools: Sketch, VSCode
tags: Vue, Buefy, SCSS, YouTubeAPI, Netlify
order: 2
active: true
---

## Project Details

I know, I know. _Another_ pomodoro app? What is this, baby’s first program? Before you roast me _too_ much, I saw this video about an idea called Animedoro by Josh Chen and was immediately struck by inspiration. Now, I'm a full on weeb and love anime but to be frank I don’t always want to watch it, so instead I decided to make it pull YouTube videos instead.

So, I’d like to think I’m bringing a little something new to the table with this timer, and it’s miles better than my <a href="https://codepen.io/bubbowrap/details/epqJoq" rel="noopener noreferrer" target="_blank">actual first pomodoro timer</a>. But hey, progress, right?

The main concepts used in this project:

- **Vue.js** to build out the project
- **Axios** to pull data from the Youtube API
- **Buefy** for UI

This is the first _personal_ project in awhile that I decided to design/figure out the experience for without relying on a framework like Vuetify to inform my design decisions. As a result I used the **Buefy** framework instead which is much lighter and saved me a lot of time on functionality but was highly customizable at the same time.

I started with **Sketch** to map out the initial look and feel. The main ideas were ‘Bold’ and ‘Minimalist’ and ‘Non-distracting,’ something that I think comes across pretty well in the final result.

Next I built out the layout and UI with **Vue.js**, and once I had all of the pieces in and it was looking good on all viewports, I went through to add in the logic/reactivity for the timer itself. After that I grabbed information from the YouTube api using Axios to load in the most popular music videos that were under the length of the break period. Unfortunately due to the limitations of the api I couldn’t pull the user’s recommendations without some sort of scraper, but it may be something I decide to the revisit in the future along with the option to select a video category.

This was a fun little project to work on that I find myself actually using to both keep me productive _and_ discover new music. Give a try!
