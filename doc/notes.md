## Creating project

-   Initialize project: `npx create-next-app --ts`
-   Install node types: `npm install --save-dev @types/node`
-   Initialize prisma: `npx prisma init`
-   Create DB on [PlanetScale](https://planetscale.com/)
-   Connect to DB with: `pscale connect link-shortener main --port 3309`
-   Push the DB: `npx prisma db push`

-   Error: Could not resolve prisma and @prisma/client in the current project. Please install them with yarn add -D prisma and yarn add @prisma/client, and rerun npx prisma generate 🙏.

-   Prisma studio: `npx prisma studio`
