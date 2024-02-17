---
date: '2022-03-08'
title: 'klefki'
github: 'https://github.com/brokentari/klefki'
external: ''
tech:
  - Svelte
  - Golang
  - sqlc
  - Tailwind CSS
showInProjects: false
---

A Svelte/Golang web app used for storing logins. The backend uses sqlc to generate the Golang type definitions that is declared by the database table schema, while
the frontend uses JSDocs to maintain type definitions while skipping the build step of using Typescript.