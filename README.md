# Gatsby.js Starter Template

An opinionated starter template for Gatsby.js that I rely on for most of my projects.

## Included Packages

- Tailwind CSS with a configuration for extending/override default styles
- Emotion.js for a CSS-in-JS styling
- ESLint optimization that follows AirBnb's React style guide
- Pre-commit linting
- Google Analytics

## Quick start

1. **Install required dependencies**

```bash
npm install
```

2. **Run the site locally**

```bash
gatsby develop
```

Accessible via http://localhost:8000

## Configurations

1. **`tailwind.config.js`**: This file allows you to customize your Tailwind CSS's settings. Check out [Tailwind CSS documentation for more detail on how this works](https://tailwindcss.com/docs/configuration/#app).

2. **`env.SAMPLE`**: Contains the environment variables that Gatsby will need to look up in order for plugins like Google Analytics to work. You'll have to rename the file to `.env.development` for Gatsby to pick up. Also create another file called `.env.production` for your production environment.

3. **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

4. **`.eslintrc.json`**: This is a configuration file for ESLint. This template comes with ESLint that is [pre-configured with configurations defined by AirBnb](https://www.npmjs.com/package/eslint-config-airbnb).

5. **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/gatsbyjs/gatsby-starter-default)