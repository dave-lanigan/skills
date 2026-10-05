---
name: webstackv01
description: A skill that helps setup a web app with NuxtJS, ShadCN-vue for web components, Clerk for auth, Turso for database and Vercel for deployment
---

## Tech
- This app uses bun not npm or deno
- This app uses nuxtjs
- This app uses chadcnvue https://www.shadcn-vue.com/
- This app uses clerk for authentication
- This app uses turso for the database

## Pre-setup
You should install the following agent skills:

```
bunx --bun skills add unovue/shadcn-vue
bunx --bun skills add clerk/skills
bunx --bun skills add vercel-labs/agent-skills
bunx --bun skills add nextlevelbuilder/ui-ux-pro-max-skill
bunx --bun skills add tursodatabase/agent-skills
```

## Setup

If the Use the install agent skills to setup and build the application based on the user description.
You should create a .env file to put secrets locally but also the env vars built into the vercel UI should be fully usable when live.

**IMPORTANT**
- This webapp should be optimized for 
- This webapp should be installable as a smartphone app via chrome
- This webapp should be setup to be deployable to vercel
