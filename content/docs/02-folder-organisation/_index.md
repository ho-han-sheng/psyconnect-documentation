---
# Title, summary, and page position.
linktitle: Folder Organisation
summary: Layout of our repository
weight: 20

# Page metadata.
title: Folder Organisation
date: '2023-01-07T00:00:00+08:00'
type: book # Do not modify.
---

The folder layout of our repository is **extremely important**, it determines how our website is compiled and organised. While you do not need to know the purpose of every folder and file in the repository right now, you do need to know where each folder is located and their general purpose.

More up-to-date and comprehensive information regarding each folder may be acquired from the [Wowchemy documentation](https://wowchemy.com/docs/).

The structure of the repository is as follows:

```
├── .github
│   ├── workflows
|   |   ├── gh-pages.yml
├── assets
│   ├── media
│   │   ├── albums
|   |   ├── icons
│   ├── scss
├── config
│   ├── _default
|   |   ├── config.yaml
|   |   ├── languages.yaml
|   |   ├── menus.yaml
|   |   ├── params.yaml
├── content
|   ├── about
|   ├── admin
|   ├── authors
|   ├── contact
|   ├── event
|   ├── home
|   ├── people
|   ├── post
|   ├── resources
|   ├── _index.md
├── data
|   ├── fonts
|   ├── themes
├── public
├── resources
├── static
├── .gitignore
├── .hugo_build.lock
├── go
├── go.sum
├── LICENSE
├── netlify.toml
├── README.md
└── theme.toml
```

## `.github`

This folder contains code for continuous integration / continuous deployment (CI/CD). It currently has one file `gh-pages.yml` which automates the publishing of our website through GitHub Pages whenever a commit is pushed to the main branch.

## `public`

Do not modify. Folder automatically created by hugo when deploying the website.

## `resources`

Do not modify. Folder automatically created by hugo when deploying the website.
