---
title: NextJS Prisma
description: A NextJS app using Prisma with a PostgreSQL database
tags:
  - next
  - prisma
  - postgresql
  - typescript
---

# NextJS Prisma Example

This example is a [NextJS](https://nextjs.org/) todo app that uses
[Prisma](https://www.prisma.io/) to store todos in Postgres.

```typescript
Prisma is a next-generation ORM that can be used to access a database in Node.js and TypeScript applications. In this guide, you'll learn how to implement a fullstack sample blogging application using the following technologies:
Next.js as the React framework
Next.js API routes for server-side API routes as the backend
Prisma as the ORM for migrations and database access
PostgreSQL as the database
NextAuth.js for authentication via GitHub (OAuth)
TypeScript as the programming language
Vercel for deployment
You'll take advantage of the flexible rendering capabilities of Next.js by using Static-Site Generation (SSG) and Server-Side Rendering (SSR) where it makes sense. At the end, you will deploy the app to Vercel.
```

## ✨ Features

- Prisma
- NextJS
- Postgres
- TypeScript

## 💁‍♀️ How to use

- [Provision a Postgres container on Railway](https://dev.new)
- Connect to your Railway project with `railway link`
- Migrate the database `railway run yarn migrate:dev`
- Run the NextJS app `railway run yarn dev`

## 📝 Notes

This app is a simple todo list where the data is persisted to Postgres. [Prisma
migrations](https://www.prisma.io/docs/concepts/components/prisma-migrate#prisma-migrate)
can be created with `railway run yarn migrate:dev` and deployed with `railway run yarn migrate:deploy`. The Prisma client can be regenerated with
`yarn generate`.

[swr](https://swr.vercel.app/) is used to fetch data on the client and perform optimistic updates.
