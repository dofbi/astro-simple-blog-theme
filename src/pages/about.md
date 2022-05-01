---
title: "About"
date: 2022-04-29T06:51:00Z
slug: "about"
description: "simple blog is a simple blog theme for Astro. It is a fork of the simple blog theme for Hugo."
layout: "../layouts/PostLayout.astro"
---

# Astro Simple blog theme

simple blog is a simple blog theme for [Astro](https://docs.astro.build).

## Demo

[View Creek on Netlify](https://astro-theme-creek.netlify.app/)

## Credits

This theme is built upon a theme called [simple-blog](https://github.com/10mohi6/hugo-theme-simple-blog) for [hugo](https://gohugo.io/). Full design credit goes to [10mohi6](https://github.com/10mohi6).

## Features

- based on [bootstrap](https://getbootstrap.com/)
- pagination
- tags
- categories

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
|:----------------  |:-------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## 👀 Want to learn more?

Feel free to check [our documentation](https://github.com/withastro/astro) or jump into our [Discord server](https://astro.build/chat).

## Site Configuration

```json
  // src/config.cjs
  // Web site base url
  siteBaseUrl: '/',
  // Web site language
  siteLanguage: "en",
  //Web site title. It is visible in sidebar and browser
  siteTitle: "Astro Themes",
  //Web site desciption. It is visible in sidebar. Also added head meta data.
  siteDescription: "<your site description>",
  //Override footer text.
  siteCopyright: "© 2020 copyright text.",
  //Site global date format. [dayjs](https://day.js.org/docs/en/display/format)
  dateFormat: "MMMM D, YYYY",
  // Pagination number of posts per page
  paginate: 6,
  //Customize the menu
  memus:[
    {
      identifier: "about",
      name: "About",
      url: "/about/",
    }
  ],
```

## Support

If this template helped you, buy me a coffee.

<a href="https://www.buymeacoffee.com/51JrBtX" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## License

This template is MIT licensed.
