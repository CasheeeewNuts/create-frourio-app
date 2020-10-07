# create frourio app

<div align="center">
  <img src="https://frouriojs.github.io/frourio/assets/images/ogp.png" width="1280" alt="frourio" />
</div>

<div align="center">
  <a href="https://www.npmjs.com/package/create-frourio-app">
    <img src="https://img.shields.io/npm/v/create-frourio-app" alt="npm version" />
  </a>
  <a href="https://www.npmjs.com/package/create-frourio-app">
    <img src="https://img.shields.io/npm/dm/create-frourio-app" alt="npm download" />
  </a>
  <a href="https://github.com/frouriojs/create-frourio-app/actions?query=branch%3Amaster++">
    <img src="https://github.com/frouriojs/create-frourio-app/workflows/Node.js%20CI/badge.svg?branch=master" alt="Node.js CI" />
  </a>
  <a href="https://github.com/frouriojs/create-frourio-app/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/create-frourio-app" alt="License" />
  </a>
</div>

<p align="center">Create a <a href="https://github.com/frouriojs/frourio">frourio</a> project in seconds</p>
<br />
<br />

## Usage

Make sure you have [npx](https://www.npmjs.com/package/npx) installed (`npx` is shipped by default since [npm](https://www.npmjs.com/get-npm) `5.2.0`)

```bash
npx create-frourio-app <my-project>
```

Or starting with npm v6.1 you can do:

```bash
npm init frourio-app <my-project>
```

Or with [yarn](https://yarnpkg.com/en/):

```bash
yarn create frourio-app <my-project>
```

## Features :tada:

1. Core framework of frourio:
   - [Fastify (5x faster than Express)](https://www.fastify.io/)
   - [Express](https://expressjs.com/)
1. Frontend framework:
   - [Next.js](https://nextjs.org/learn/excel/typescript)
   - [Nuxt.js](https://typescript.nuxtjs.org/)
1. Next.js building mode:
   - Basic (next build)
   - [Static (next build && next export)](https://nextjs.org/docs/advanced-features/static-html-export)
1. Nuxt.js rendering mode:
   - [Universal (SSR / Static)](https://nuxtjs.org/guide/#server-rendered-universal-ssr-)
   - [SPA](https://nuxtjs.org/guide/#single-page-applications-spa-)
1. Nuxt.js deployment target:
   - [Server (Node.js hosting)](https://nuxtjs.org/api/configuration-target)
   - [Static (Static/JAMStack hosting)](https://nuxtjs.org/api/configuration-target)
1. HTTP client of aspida:
   - [axios](https://github.com/axios/axios)
   - [fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
1. Package manager:
   - Yarn
   - Npm
1. Daemon process manager:
   - None
   - [PM2](https://pm2.keymetrics.io/)
1. O/R mapping tool:
   - [Prisma (recommended)](https://www.prisma.io/)
   - [TypeORM](https://typeorm.io/)
   - None
1. Database type of Prisma:
   - [MySQL](https://www.mysql.com/)
   - [PostgreSQL](https://www.postgresql.org/)
   - [SQLite](https://www.sqlite.org/)
1. Database type of TypeORM:
   - [MySQL](https://www.mysql.com/)
   - [PostgreSQL](https://www.postgresql.org/)
   - [MongoDB](https://www.mongodb.com/)
   - [Sql Server](https://www.microsoft.com/en-us/sql-server)
   - [MariaDB](https://mariadb.com/)
   - [CockroachDB](https://www.cockroachlabs.com/)

## Support

<a href="https://twitter.com/solufa2020">
  <img src="https://aspida.github.io/aspida/assets/images/twitter.svg" width="50" alt="Twitter" />
</a>

## License

create-frourio-app is licensed under a [MIT License](https://github.com/frouriojs/create-frourio-app/blob/master/LICENSE).
