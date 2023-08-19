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

## `content`

### `content/about`

Content for the "About Us" page.

### `content/admin`

Configuration files for the unused internal content management system (CMS)

### `content/authors`

Database of authors for tagging to resources and display on "People" page.

### `content/contact`

Content for the "Contact Us" page.

### `content/event`

Content for the "Events" page.

### `content/home`

Content for the "Home" page.

### `content/people`

Content for the "People" page

### `content/post`

Content for an unused page.

### `content/resources`

Content for the "resources" page.

### `content/_index.md`

File that determines our "Hero" page. i.e., the first page everyone lands on.

## `data`

### `data/fonts`

Folder for containing custom fonts (if any).

### `data/themes`

Folder for dark / light themes used.

## `public`

Do not modify. Folder automatically created by hugo when deploying the website.

## `resources`

Do not modify. Folder automatically created by hugo when deploying the website.
