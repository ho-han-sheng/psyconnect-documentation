---
title: Setting Up Visual Studio Code
linktitle: Setting Up Visual Studio Code
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 20
---

1. On startup, you will be greeted with the `Get Started` page. A few options are available, you would want to use `Open Folder`.

![Screenshot of VSCode Welcome Page](vscode-welcome.png)

1. This opens the native Windows Explorer. Navigate to the location you saved your local, cloned repository to as specified in [Cloning-the-fork-to-local-computer](Getting-Started.md#cloning-the-fork-to-local-computer). Ensure that the folder selected is correct, i.e., `PsyConnect.github.io`.
   
    (A) This can be achieved by single-clicking the corresponding folder.

    ![Screenshot of Windows Explorer](folder-selection-1.png)

    (B) Or, by double-clicking into the folder.

    ![Screenshot of Windows Explorer](folder-selection-2.png)

2. Click on `Select Folder`. You should now see the repository's folder structure.

![Screenshot of VSCode](folder-selection-3.png)

## VSCode Extensions

The base installation of VSCode does not come with  functionalities specific to the programming language you use, this prevents unnecessary downloads for features you don't need. Consequently, you need to install these extensions yourself. Fear not for VSCode has a relatively quick and simple installation process for them.

Suggested extensions:

- bungcip.better-toml
  - Provides syntax highlighting for `.toml` (Tom's Obvious Minimal Language) files
- rusnasonov.vscode-hugo
  - Allows you to locally build and host a `hugo` server
  - i.e., locally view your changes to the website without affecting the live website
- budparr.language-hugo-vscode
  - Provides syntax highlighting and snippets for `hugo` websites
- yzhang.markdown-all-in-one
  - Provides auto preview and other shortcuts for `.md` (Markdown) files
- DavidAnson.vscode-markdownlint
  - Lint (a static code analysis tool used to flag programming errors, bugs, stylistic errors and suspicious constructs) for `.md` (Markdown) files
- natqe.reload
  - Provides a reload button on the bottom right of VSCode.
- tonybaloney.vscode-pets
  - Provides a virtual pet to keep you company when working in VSCode

Here are the steps for installing an extension in VSCode:

1. On the leftmost bar, select the extensions icon.

![Screenshot of vscode extensions](vscode-ext-1.png)

1. Input the extension ID of the aforementioned extensions. e.g., `DavidAnson.vscode-markdownlint`

![Screenshot of vscode extensions search bar](vscode-ext-2.png)

1. Click on the install button.

![Screenshot of homepage of vscode extension](vscode-ext-3.png)

1. Your `install` button should now be replaced with a `disable` and `uninstall` button.

![Screenshot of installed vscode extension](vscode-ext-4.png)

1. Repeat this process for the remaining extensions

2. Reload VSCode to ensure changes take effect. If you have installed `natqe.reload`, there will be a reload button on the bottom right.

![Screenshot of reload button](vscode-ext-5.png)
