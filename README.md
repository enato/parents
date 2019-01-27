# Parents CMS

This repo contains an online website that is built with [Gatsby](https://www.gatsbyjs.org/), and [Netlify CMS](https://www.netlifycms.org): **[Demo Link](https://gatsby-netlify-cms.netlify.com/)**.

It is based on this repo: [netlify-templates/gatsby-starter-netlify-cms](https://github.com/netlify-templates/gatsby-starter-netlify-cms).

It follows the [JAMstack architecture](https://jamstack.org) by using Git as a single source of truth, and [Netlify](https://www.netlify.com) for continuous deployment, and CDN distribution.

## Prerequisites

- Node (I recommend using v8.2.0 or higher)
- [Gatsby CLI](https://www.gatsbyjs.org/docs/)

## Getting Started (Recommended)

### Development
```
$ git clone https://github.com/enato/parents.git
$ cd parents
$ yarn
$ npm run develop
```

To test the CMS locally, you'll need run a production build of the site:
```
$ npm run build
$ npm run serve
```
