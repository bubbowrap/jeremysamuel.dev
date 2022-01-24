---
title: Statlify
description: View your top artists, tracks, genres, and more.
category: Design, Development
role: Design, Front-end Development, Back-end Development
link: https://statlify.netlify.app/
github: https://github.com/bubbowrap/spotify-userspace
thumbnail: statlify/statlify-thumb.jpg
slides:
  [
    'statlify/statlify-mobile-pg.jpg',
    'statlify/statlify-login-pg.png',
    'statlify/statlify-home-pg.jpg',
    'statlify/statlify-stats-pg.jpg',
    'statlify/statlify-playlist-pg.jpg',
  ]
alt: Statlify Dashboard Screenshot
client: Personal Project
tools: VSCode, Figma, Spotify API, Netlify CLI
tags: React, Typescript, Styled Components, Serverless Functions, Netlify
order: 1
active: true
---

## Project Details

Project to try out the Spotify API and help users see where their true interests lie. It shows a user's Spotify stats in a bunch of neat ways.

A lot of interesting things to figure out with this project. Hand designed in **Figma** and styled from the ground up with **Styled Components** solely because I felt like I didn't need a whole heavy css framework for something so relatively simple, y'know? Plus with design, if you don't use it you lose it (that's probably not actually true) and I saw it as a neat opportunity to brush off the skills.

### Development

The main things I used in this project are:

- React
- Typescript
- Styled Components
- Chart.js
- Spotify API
- Serverless Functions
- Netlify

As mentioned above I used **React** to build out the UI/functionality, and more _specifically_:

- **Context API** for state management
- **Fetch API** to grab user data from Spotify
- **React Router** for navigation/routing

There's also a **custom hook** in there. Neat.

One of the more interesting things was having to rewrite the node.js server I'd initially used for Spotify authorization as a few serverless functions instead, and I even used the Netlify CLI for development which was surprisingly handy and makes me much more willing to use it in the future.

Finally, I deployed the app directly from Github with **Netlify**.

You can see the app at [https://statlify.netlify.app](https://statlify.netlify.app).
