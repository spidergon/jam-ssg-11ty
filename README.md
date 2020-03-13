# Daily Briefing

Get your daily briefing of motivation messages, daily hot news (localized by country) and your current weather.

## Overview

This site is comprised of static files generated by [Eleventy](https://11ty.dev) for simplified deployment and hosting.

## Local development

To build the site you need:

- [Node](https://nodejs.org) - to run the build
- [Yarn](https://yarnpkg.com) - to install and manage dependencies

### Getting started

```bash
# clone this repository
git clone git@github.com:spidergon/daily-briefing.git

# go to the working directory
cd daily-briefing

# install dependencies
yarn

# start a local build server with hot reloading
yarn start
```

## 💫 Deployment

[![Netlify Status](https://api.netlify.com/api/v1/badges/1743f9dd-72ce-4af7-94cf-0fb117d59446/deploy-status)](https://app.netlify.com/sites/daily-briefing/deploys)

The build command `yarn run build` will generate a set of static assets in a `dist` folder which can be deployed to any web hosting service.

My preferred method is to host on [Netlify](http://www.netlify.com) which can run this build process in a CI environment and then deploy the build to automatically to a global CDN. Such deployments are [triggered automatically](https://www.netlify.com/docs/continuous-deployment/) by every git push to the `master` branch of the origin repository.

## Clone and deploy your own

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/spidergon/daily-briefing)
