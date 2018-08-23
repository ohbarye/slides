## If you:

- want to contribute OSS
- are struggling to find a repository or an issue to contribute
- (would rather you preferred major OSS)

This talk would be helpful to you.

---

## Agenda

***

1. Story so far
2. Current status
3. What's next?

---

# Story so far 📝

---

## Current problem is...

---
## Contribution Accessibility

<image src="./before.png" width="100%">

---

## Ideal world

<image src="./after.png" width="100%">

---

## Story so far

***

At the previous Roppongi.js.
I've shared a simple script to fetch good first issues from GitHub.

---

## what is "good first issue"?

***

<image src="./labels.png" width="40%">

---

> Apply the `help wanted` and `good first issue` labels to issues in your repository to highlight opportunities for people to contribute to your project.

https://help.github.com/articles/helping-new-contributors-find-your-project-with-labels/

---

## Previous output

***

I could make Good first issue list.
But not cool. I felt I should implement GUI for better usability.

<image src="./list.png" width="100%">

---

## Response

***

<image src="./previous_slide.png" width="100%">

---

# Current status 🐶

---

<image src="./goofi_demo.gif" width="90%">

---

## Features

***

- List up repos and issues filtered by language
- Single Page Application built with React

---

<image src="./architecture.png" width="100%">

---

## What I did

***

- Implemented frontend and backend
  - React, Material UI, TypeScript
  - Node.js, Express, GraphQL
- Deployed on Netlify
  - Integrate Netlify to deploy automagically
- Use Docker Compose on development

---

## Interested?

***

See:

- App https://goofi.netlify.com/
- Implementation https://github.com/ohbarye/goofi

---

# What's next? 🔜

---

## Current issues

***

The current goofi has 2 major issues.

- Performance
  - It queries against GitHub for every request
  - No cache
- Rate limit
  - GitHub's constraint: 5,000 requests/day

---

## Solution

***

- Next.js, SSR, PWA, server side cache
- They come from https://github.com/hanford/trends
- Aim to get perfect score of Lighthouse

---

<image src="./new_architecture.png" width="100%">

---

## Q. Possible? 🤔

---

## A. Not sure. Please give me advice. 🙏

---

## Let's find your "good first issues"
## with "goofi" and contribute! 💪

Go https://goofi.netlify.com/

---

### Who?

<image src="./me.jpeg" width="20%">

***

- @ohbarye http://ohbarye.me/
- Web Developer / Engineering Manager
- Working for [Quipper](https://www.quipper.com/)
