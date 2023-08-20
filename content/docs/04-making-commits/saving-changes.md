---
title: Saving Changes
linktitle: Saving Changes
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
---

## Save your work

Once you are satisfied with the look of your edit (through the [local hugo server](../03-making-edits/hosting-local-hugo-server.md)), remember to save your changes to the markdown (`.md`) file. You may save with the keyboard shortcut (Ctrl-S) or with the ribbon buttons at the top of VSCode.

![Screenshot of VSCode save menu](making-commits-1.png)

A quick way to tell if you have saved your edits in the current file would be to look at the "close" icon to the right of the file tab. 

This is what an unsaved file with edits appears as, a circle.

![Unsaved markdown file](commits-unsaved.png)

And this is a saved file, a cross.

![Saved markdown file](commits-saved.png)

You may also notice letters beside certain edited files. You may hover over them to find out what they refer to. Below are some examples of the letters you may encounter:

* __A__ - Added; This new file was just added to the repository
* __M__ - Modified; The contents of this existing file have been edited
* __D__ - Deleted; This file will be deleted
* __U__ - Untracked; This file was newly added and is not tracked by Git yet. You have to "stage" these files which will be elaborated on below.
* __C__ - Conflict; This file currently conflicts with a file in the original repository, most likely as a duplicate or multiple people have made changes to the same file.
* __R__ - Renamed; The file has been renamed

The numbers indicate how many possible formatting errors are present in the file, usually a deviation from markdown (`.md`) conventions. Your linting extension will underline these errors.

![Alt text](commit-letter-number.png)

![Alt text](linting-warning.png)

## Commit your changes

It's time to switch back to GitHub Desktop. You will now notice that a bunch of files that you have added or modified are now listed as shown (the exact names of the files may differ, the point is that these are the files Git has identified changes in and have not yet been committed).

![Screenshot of stashed changes](github-stashed.png)

At the bottom-left, you will see input fields: __Summary__ and __Description__. 

> Summary is __compulsory__, use a short message to describe what edits you have made. Keep the summary concise and to the point, any elaborations may be indicated in the description below.
> e.g., "Added event post for july botanic gardens", "Changed author image", "Updated EXCO positions".

Reminder: Commit messages are __PUBLIC__.

![Screenshot of commit message field](commit-message.png)

Once done, click "commit to [branch-name-here]".

![Screenshot of committed](committed.png)

Congratulations! You have committed your changes onto a "permanent timeline" of all edits made to the repository. To recap, this commit acts as a "checkpoint", allowing us to:

1. Restore the entire repository to a previous state (if anything breaks)
2. Keep track of who, what, and when changes were made (so I know who to blame, kidding)
3. Resolve file conflicts in multiple copies of the repository when working collaboratively

Do read up on the [git commits best practices](https://gist.github.com/luismts/495d982e8c5b1a0ced4a57cf3d93cf60).

## Push commits to remote repository

Importantly, the commit you just made is a local one. This means that the commit is currently only tracked on your __local copy__ of the repository; If you are currently working on one device, the changes and commits will not be reflected on another device yet.

To have the commit reflected on the [remote copy you made](../01-getting-started/forking-the-repo.md), you need to `push` the commit to the origin repository (i.e., your forked repository on GitHub) by clicking the button below:

![Screenshot of push to origin](push-origin.png)
