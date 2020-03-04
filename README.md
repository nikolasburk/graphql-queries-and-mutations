# GraphQL Apollo Server Example

<!-- This example shows how to implement a **GraphQL server with TypeScript** based on  [Prisma Client](https://github.com/prisma/prisma2/blob/master/docs/prisma-client-js/api.md), [apollo-server](https://www.apollographql.com/docs/apollo-server/) and [GraphQL Nexus](https://nexus.js.org/). It is based on a SQLite database, you can find the database file with some dummy data at [`./prisma/dev.db`](./prisma/dev.db). -->

## How to use

### 1. Download example & install dependencies

Clone this repository:

```
git clone git@github.com:nikolasburk/graphql-queries-and-mutations.git --depth=1
```

Install npm dependencies:

```
cd graphql-queries-and-mutations
npm install
```


### 2. Start the GraphQL server

Launch your GraphQL server with this command:

```
npm run dev
```

Navigate to [http://localhost:4000](http://localhost:4000) in your browser to explore the API of your GraphQL server in a [GraphQL Playground](https://github.com/prisma/graphql-playground).

> The schema that specifies the API operations of your GraphQL server is defined in [`./schema.graphql`](./schema.graphql). 