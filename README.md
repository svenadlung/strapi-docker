# Strapi docker boilerplate using MongoDB

### Install

First start takes some time to initialize, take a cup of ☕️ and relax.

- Important: create directory before starting `mkdir api`
- docker-compose up

### Usage

Open `http://localhost:1337/admin`

Print version of strapi: `cd api && ./node_modules/strapi/bin/strapi.js version`

## Plugins

### E-Mail provider

- https://www.npmjs.com/search?q=strapi-provider-email-

Install:

`cd api && yarn add strapi-provider-email-nodemailer`

Use administration panel and go to `Plugins` -> `Email` -> `Providers` choose `nodemailer` and start configuration
