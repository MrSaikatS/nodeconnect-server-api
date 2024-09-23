# Welcome to NodeConnect!

This is a basic full-stack social media application called **NodeConnect.** The application is split into two distinct projects/repositories, adhering to the microservice architecture.

- Frontend -> [`nodeconnect-web-ui`](https://github.com/MrSaikatS/nodeconnect-web-ui)
- Backend -> [`nodeconnect-server-api`](https://github.com/MrSaikatS/nodeconnect-server-api)

> **This repository represents the backend part of the application.**

## Getting Started

**_Step 1._** Install and the dependencies.

```bash
npm i
```

**_Step 2._** Bootstrap the application.

```bash
npm run bootstrap
```

**_Step 3._** Migrate database schema.

```bash
npm run db:apply
```

**_Step 4._** Start the backend server.

```bash
npm start
```

## Some important things to keep in mind

**_First,_** Don't forget to generate a snapshot of your current data model by running:

```bash
npm run db:snapshot
```

**_Second,_** If you upgrade the Directus version manually, then don't forget to Migrate the database to match the versions of Directus by running:

```bash
npm run db:up
```
