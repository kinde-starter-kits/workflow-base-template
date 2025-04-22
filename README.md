# ⚙️ Kinde Workflow base template

This repository contains a base template **TypeScript workflows** for [Kinde](https://kinde.com).

## 🧠 What Are Kinde Workflows?

Kinde Workflows let you run custom JavaScript/TypeScript logic **during the authentication process**, giving you full control over:

- User onboarding
- Role and permission assignment
- Profile enrichment
- Custom validation or access control
- Third-party service integration

All code is executed **server-side on Kinde**, meaning you don’t need to host or deploy anything yourself.

## What is included in this repo?

This is the simplest example of a Kinde workflow. It is triggered on the [user post authentication](https://docs.kinde.com/workflows/example-workflows/workflow-user-post-auth/) event and logs "Hello world" to the console.

## Get started

1. Clone this repo
2. Log into your Kinde account
3. [Connect this repo](https://docs.kinde.com/workflows/about-workflows/connect-repo-for-workflows/#connect-your-repo-and-branch) to Kinde
4. Log a user into your app
5. Check the runtime logs for the workflow
