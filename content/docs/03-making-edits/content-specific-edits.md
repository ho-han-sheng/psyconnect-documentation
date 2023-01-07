---
title: Content Specific Edits
linktitle: Content Specific Edits
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 30
---

## Creating an event post

1. Navigate to `content/event`.

![Screenshot of event folder](../assets/images/event-folder.png)

2. You will notice that each individual event has their own folder. Right click any existing event folder (e.g., starred-up-psyconnect-movie) and copy them.

![Screenshot of event folder](../assets/images/event-folder-2.png)

3. Right click the parent `event` folder and paste a copy of the existing event folder.

![Screenshot of event folder](../assets/images/event-folder-3.png)

4. Rename the folder to reflect your event (e.g., november-board-games).

> ❗ The folder's name determines the public URL of the page, so ensure that it does not contain anything unprofessional.
> Also note to follow the convention of using `-` in place of spaces.

![Screenshot of event post url](../assets/images/event-url.png)

5. Open up the `index.md` file.

6. Replace the existing information. Minimally, the `Title`, `location`, `address`, `date`, `date_end`, and `publishDate` should be filled.

![Screenshot of event index](../assets/images/event-index.png)

7. For the write-up of the event, place them under the second `---`.

![Screenshot of event index](../assets/images/event-body-demarcation.png)

8. For the accompanying picture, replace `featured.jpg` with the image you wish to use. You can replace it with either VSCode's built-in file explorer OR your operating system's file explorer.

> ❗ You **must** use `featured.jpg` as the name of the picture, otherwise hugo will not know which picture to use.

![Screenshot of local repo in windows file explorer](../assets/images/file-explorer.png)

## Creating a resource

1. Navigate to `content/resources`.

![Screenshot of resources folder](../assets/images/resources-folder-1.png)

1. Repeat steps 2 to 7 with any existing resource folder and its `index.md`.

> ❗ For resources, minimally `title`, `authors`, `date`, `publishDate`, and `publication_types` must be filled.

![Screenshot of resources index](../assets/images/resources-index.png)

3. For the resource itself (e.g., the PDF file), upload it to the same folder **with the same name as its folder** (e.g., `resources/MTH220-summary-sheet` contains `MTH220-summary-sheet.pdf`). This allows hugo to automatically link the pdf or other files to the current resource post.

![Screenshot of resources pdf](../assets/images/resources-folder-2.png)
