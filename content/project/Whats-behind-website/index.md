---
title: "What's behind a website?"
date: 2023-03-03T13:55:47+08:00
# weight: 1
# aliases: ["/first"]
tags: ["web"]
author: "SamChen"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "Step 1: Installation"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: false
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://sc0210.github.io/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: false # to append file path to Edit link
---
## 🔥Blog website (Demo)

{{< figure src="./images/website-profilo-page.jpg" align=center title="Profilo-page of my personal website" caption="Check out by clicking on the image!!☝🏻"  link="https://sc0210.github.io/" >}} 

{{< figure src="./images/website-blog-page.jpg" align=center title="Blog-page of my personal website" caption="Check out by clicking on the image!!☝🏻" link="https://sc0210.github.io/blog" >}} 

----

## Mindset for self-taught

> It might get tough in the process, make sure you...

Before diving into anything new, it's both wise and helpful to have a blueprint or plan in mind. Whenever I begin to learn something new or start a side project, I make sure to create a clear path to success by following a few simple steps. These steps include:

- **Goal**: **What** you want to achieve or problem to solve.
- **Reason**: **Why** you set this for your goal.
- **Methods/Tools**: **What** tools might I need to get there. 

Since it's normal to get stuck in the work process, it's easy to become frustrated and lose sight of our goals. However, **it's important to keep this in mind and stay focused on what and why we're building.** 

>By reminding ourselves of our initial goals and reasons for embarking on the project, we can maintain our **motivation** and remain dedicated to achieving success.

----

## Installation 
> Installation might varies from the operaiton system, check out official installation steps on HUGO website (https://gohugo.io/installation/)

1. [Git (version control)](https://git-scm.com/)
```
# Via homebrew (package manger)
$ brew install git
```

2. [Go (Backend development)](https://go.dev/doc/install)

3. [Hugo (Backend framework built on Go)](https://gohugo.io/)
```
# Via homebrew (package manger)
$ brew install hugo
```
4. [*Optional: VScode (editior)*](https://code.visualstudio.com/download)

5. [*Optional: Hugo-theme -> PaperMod*](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-faq/)

```
# Self-recommended method (submodule)
$ git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
$ git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)

# Update themes
$ git submodule update --remote --merge
```

----

## Online resourse
- [Hugo official website](https://gohugo.io/)
- [Hugo-papermod website](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-faq/)