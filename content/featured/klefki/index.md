---
date: '1'
title: 'klefki'
cover: './klefki.png'
github: 'https://github.com/brokentari/klefki'
external: ''
tech:
  - Svelte
  - Golang
  - sqlc
  - Tailwind CSS
---

A Svelte/Golang web app used for storing logins. The backend uses sqlc to generate the Golang type definitions that is declared by the database table schema, while
the frontend uses JSDocs to maintain type definitions while skipping the build step of using Typescript.