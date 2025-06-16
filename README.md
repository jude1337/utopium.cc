![image](https://cdn.7udas.cc/utopium.cc)

<p align="center">
  <a href="https://utopium.cc/">
    <h1 align="center">utopium.cc</h1>
  </a>
</p>

<p align="center">
utopium.cc is a multifuntional invite-only forum.
</p>
<p align="center">
  <a href="https://t.me/jud6s">
    <img src="https://img.shields.io/badge/-jud6s-blue?style=plastic-square&logo=Telegram&logoColor=white&link=https://t.me/jud6s" alt="Telegram" />
  </a>
</p>
<br/>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">About The Project</a>
    </li>
    <li>
      <a href="#techstack">Getting Started</a>
    </li>
    <li><a href="#features-technical">Features</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
  </ol>
</details

<hr />

## Introduction

In this repository, you'll find **snippets of code** from my development of utopium.cc inside the `/snippets` folder.  
Additionally, the `/images` folder contains **actual screenshots** of various pages, features and UI elements of the platform.

Further down, you can explore the **actual (or nearly complete) folder structure** of the project.

## Techstack

- nextjs 15 - framework
- typescript - language
- tailwindcss - css
- mysql - database
- drizzle - orm
- zustand - global state management
- zod - validation
- mailersend - emails
- stripe - payments
- vitest - tests

## Features (technical)

- server-side rendering (SSR)
- static site genetation (SSG)
- incremental static regeneration (ISR)
- dynamic generated opengraph images
- discord webhooks
- rich text editor
- advanced effects/animations created with canvas
- media proxy (cors)
- file uploading
- integrations and embeds with spotify, discord, soundcloud, roblox, yt, twitch, steam
- reordering links, widgets, badges etc.
- promise toasts
- debounced auto save forms
- metadata customization
- google fonts integration
- analytics (top links, total and unique views, audience geo)
- discord linking (oauth)
- admin dashboard for user management and editing articles
- integrates with deezer api for custom music player widget
- live biolink preview (zustand)
- audio visualizer (analyzes and visualizes audio frequency)
- responsive modals (native drawers for mobile and dialog for desktop)

For all features, go to [docs](https://utopium.cc/docs)

## Project Structure

```
  ├── app
  │   ├── (casino)
  │   ├── (dashboard)
  │   ├── (docs)/docs
  │   │   └── [[...slug]]
  │   ├── (profiles)
  │   ├── (website)
  │   │   ├── (auth)
  │   │   ├── (marketing)
  │   │   └── (onboarding)
  │   │       ├── layout.tsx
  │   │       └── template.tsx
  │   ├── api
  │   ├── error.tsx
  │   ├── not-found.tsx
  │   ├── providers.tsx
  │   ├── manifest.ts
  │   ├── robots.ts
  │   ├── sitemap.ts
  │   └── ...
  ├── components
  │   ├── biolink
  │   ├── casino
  │   ├── core
  │   ├── editor
  │   ├── layout
  │   ├── form
  │   └── email
  ├── hooks
  ├── utils
  │   ├── functions
  │   ├── validations
  │   ├── constants
  │   └── index.ts
  ├── lib
  │   ├── application
  │   │   ├── metadata
  │   │   ├── tracks
  │   │   ├── widgets
  │   │   ├── analytics
  │   │   │   ├── actions
  │   │   │   ├── constants.ts
  │   │   │   ├── format.ts
  │   │   │   ├── types.ts
  │   │   │   └── utils.ts
  │   │   ├── orders
  │   │   ├── templates
  │   │   └── ...
  │   ├── auth
  │   ├── stores
  │   ├── drizzle
  │   ├── services
  │   ├── drizzle
  │   ├── zod
  │   ├── webhook.ts
  │   ├── email.ts
  │   ├── database.ts
  │   ├── api.ts
  │   ├── stripe.ts
  │   └── ...
  ├── public
  ├── tests/casino
  └── ...
```

### Showcase (old)

Small showcase of some features such as tilting card, audio visualizer and thunder effect.

https://github.com/user-attachments/assets/250a19aa-0b7a-48ed-9dfb-a129b6cf737f
