## Agenda

***

1. Story so far (1 min)
2. Current status (2 min)
3. What's next? (2 min)

---

## If you:

- want to contribute OSS
- are struggling to find a repository or an issue to contribute
- (would rather you preferred major OSS)

This talk would be helpful to you.

---

# Story so far 📝

---

## Story so far

***

I've shared the followings at the previous Roppongi.js.

- I was looking for a better way to find out OSS/issues that I can contribute.
- "good first issue" label on GitHub is a nice clue.
- I created a simple script to fetch good first issues with GitHub GraphQL API v4, and shared a list of such issues.

>>>

## Response

***

<image src="./previous_slide.png" width="100%">

>>>

## what is "good first issue"?

***

<image src="./labels.png" width="40%">

>>>

> Apply the `help wanted` and `good first issue` labels to issues in your repository to highlight opportunities for people to contribute to your project.

https://help.github.com/articles/helping-new-contributors-find-your-project-with-labels/

>>>

## Previous output

***

I could make Good first issue list.
But not cool. I felt I should implement GUI for better usability.

<image src="./list.png" width="100%">

---

# Current Status 🐶

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

## Current problems

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
