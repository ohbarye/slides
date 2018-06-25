## If you:

- want to contribute OSS
- are struggling to find a repository or an issue to contribute
- (would rather you preferred major OSS 😇)

This talk would be helpful to you.

---

## Content

A tip to find "Good First Issues" with a script to make an issue list.

- This talk focuses on just a way to find them.
- See [OSS貢献超入門](https://www.slideshare.net/shigemk2/oss-78585757) if you want to know next steps.

---

## Issue List

First of all, see the "good first issue" [list](https://docs.google.com/spreadsheets/d/1-2jhSCFZUWyFsubCnGiX-xui9nA76M783Z2SOfVrEU4/edit#gid=440574128).

<image src="./list.png" width="100%">

>>>

## BTW, what is "good first issue"?

***

<image src="./list.png" width="100%">

>>>

> Apply the `help wanted` and `good first issue` labels to issues in your repository to highlight opportunities for people to contribute to your project.

https://help.github.com/articles/helping-new-contributors-find-your-project-with-labels/
---

## How to make the list

---

To make it, I wrote a simple script in https://github.com/ohbarye/goofi.

***

1. Call GitHub GraphQL API
2. Format its response
3. Create CSV

---

GraphQL Query

***

<image src="./query.png" width="100%">

>>>

"good-first-issues:>1"

***

<image src="./query2.png" width="100%">


ref: [GitHub help](https://help.github.com/articles/searching-repositories/#search-based-on-number-of-issues-with-good-first-issue-or-help-wanted-labels)

>>>

"stars:>500"

***

<image src="./query3.png" width="100%">

ref: [GitHub help](https://help.github.com/articles/searching-repositories/#search-by-number-of-stars)

>>>

### Response

***

<image src="./response.png" width="100%">

---

Once we can easily get data via the GitHub API, it's not a hard task to format the data.

***

<image src="./create_csv.png" width="80%">

---

Now that we have the candidate list, all we have to do is check issues one by one.

***

<image src="./list.png" width="100%">

---

## Another way

Use [Jasper](https://jasperapp.io/)

<image src="./jasper.png" width="100%">

>>>

Create a stream to find "good first issues"

***

<image src="./jasper_stream.png" width="100%">

>>>

## NOTE

I used to find issues with this way, but...

* It cannot sort repositories by stars count
* It cannot reject wrong usage of "good first issue"
* It notifies me every when an issue is updated

In short, that was too noisy.

---

## Are they really nice ways? 🤔

---

At least, I could have contributed some popular repositories even though I was not familiar with them.

***

e.g. Node.js

<image src="./contribution.png" width="100%">

---

## Let's find your "good first issues"
## And contribute! 💪

---

### Who?

<image src="./me.jpeg" width="20%">

***

- @ohbarye http://ohbarye.me/
- Web Developer / Engineering Manager
- Working for [Quipper](https://www.quipper.com/)

---

### 7/19 (Thu) 19:30-22:00

**https://techplay.jp/event/680406**

<image src="./meetup.png" width="100%">
