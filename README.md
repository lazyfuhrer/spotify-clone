# Spotify Clone app using Next.js, Tailwind CSS, Recoil

## Deployment
Deployed the app using vercel at : https://www.biswarghyabiswas.me/

## Tech Stacks
1) Next.js v12
2) Tailwind CSS v3, lodash, HeroIcons
3) NextAuth v4
4) Spotify Web API
5) Recoil for global state management for different components

## Setup react app
Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
# or
pnpm create next-app -- --example with-tailwindcss with-tailwindcss-app
```

## Spotify developer app
Link: https://developer.spotify.com/dashboard/applications
1) Go to the link and create a new app
2) Click on edit-settings and in Redirect-uris and add your domain URL and save it. ex- http://localhost:3000/api/auth/callback/spotify
3) Copy the client-id and client-secret and save it in your project as env variables.

## Resources
1) https://nextjs.org/docs
2) https://tailwindcss.com/docs/guides/nextjs
3) https://recoiljs.org/docs/introduction/installation
4) https://lodash.com/docs/4.17.15
5) https://github.com/thelinmichael/spotify-web-api-node
6) https://vercel.com/docs/concepts/next.js/overview
