# Build and Deploy: TWITTER clone with React, Tailwind, Next, Prisma, Mongo, NextAuth & Vercel (2023)

![Fullstack Twitter Clone (2)](https://user-images.githubusercontent.com/23248726/224405420-03112a76-250a-4283-992c-60e235170678.png)

This is a repository for a FullStack Twitter clone tutorial using React, NextJS, TailwindCSS & Prisma.

[VIDEO TUTORIAL](https://www.youtube.com/watch?v=ytkG7RT6SvU)

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

### Install packages

```shell
npm i
```

https://cloud.mongodb.com/
0.0.0.0/0

gitHub -> Settings -> Developer setting -> OAuth Apps
airbnb
http://localhost:3000/

google developer console
https://console.cloud.google.com/
NEW PROJECT
SELECT PROJECT
search Apis
Enabled APIs & services -> OAuth consent screen -> External -> CREATE
Credentials -> CREATE CREDENTIALS -> Create OAuth client ID
Web application
Authorized redirect URLs
http://localhost:3000/api/auth/callback/google

### Setup .env file

```js
DATABASE_URL=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

npx prisma db push

npx prisma generate

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
