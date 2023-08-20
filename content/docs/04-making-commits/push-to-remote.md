---
title: Pushing to remote
linktitle: Pushing to remote
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 20
---

## Push commits to remote repository

Importantly, the commit you just made is a local one. This means that the commit is currently only tracked on your __local copy__ of the repository; If you are currently working on one device, the changes and commits will not be reflected on another device yet.

To have the commit reflected on the [remote copy you made](../01-getting-started/forking-the-repo.md), you need to `push` the commit to the origin repository (i.e., your forked repository on GitHub) by clicking the button below:

> The number and arrow on the `Push origin` button denotes how many local commits you have made that have not yet been pushed to the remote repository.

![Screenshot of push to origin](push-origin.png)

Once GitHub Desktop completes its processes, you should now see your changes reflected in your online fork on GitHub (`your-username/PsyConnect.github.io`).

![Screenshot of remote repo](github-reflect-commit.png)