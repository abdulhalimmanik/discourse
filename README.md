# Build and Deploy: Discourse with React, Tailwind, Next, Prisma, Mongo, NextAuth & Vercel (2023)

This is a repository for a FullStack Discourse tutorial using React, NextJS, TailwindCSS & Prisma.

[VIDEO TUTORIAL](https://www.youtube.com/watch?v=ytkG7RT6SvU)

[DOCKER VERSION by mandeepsingh10](https://github.com/mandeepsingh10/chwitter)

We are going to learn funcionalities such as:

- Authentication system
- Notification system
- Image Upload using Base64 strings
- Prisma ORM with MongoDB
- Responsive Layout
- 1 To Many Relations (User - Post)
- Many To Many Relations (Post - Comment)
- Following functionality
- Comments / Replies
- Likes functionality
- Vercel Deployment

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/abdulhalimmanik/discourse.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
