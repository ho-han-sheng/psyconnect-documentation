---
title: Installing Prerequisite Software
linktitle: Installing Prerequisite Software
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 20
---

You do not need to install both [Scoop](#scoop-for-windows) and [Homebrew](#homebrew-for-macos). Choose the relevant package manager for the operating system you are working on (Windows or MacOS).

> ❗ Make sure you install a package manager before the rest of the software to prevent unnecessary headaches.

### Scoop for Windows

You may refer to [Scoop documentation](https://scoop.sh/).

1. Open Windows Powershell by typing in the search bar:

![Screenshot of search bar](/static/uploads/scoop-list.png)

1. Copy and paste the following code into the command-line (this is optional if you are not running a remote script for the first time):

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

3. You may receive a prompt alerting you to the change in execution policy, answer yes to this with Y:

![Screenshot of execution policy change](/assets/media/execution-policy-change.png)

1. Copy and paste the following code into the command-line:

```powershell
irm get.scoop.sh | iex
```

5. Wait for scoop to install

![Screenshot of scoop installation](/assets/media/scoop-install-success.png)

For the following software, you may use [scoop's search function](https://scoop.sh/) to search for the relevant installation commands (in the event that commands listed here are outdated).

![Screenshot of scoop search](/assets/media/scoop-go-search.png)

### Homebrew for MacOS

You may refer to the [Homebrew documentation](https://brew.sh/).

For the following software, you may use [homebrew's package browser](https://formulae.brew.sh/) to search for the relevant installation commands (in the event that commands listed here are outdated).

![Screenshot of homebrew search](/assets/media/homebrew-search-go.png)

### Git

[Git](https://git-scm.com/) is our VCS of choice.

For Windows scoop users, simply input the following in powershell:

```powershell
scoop install git
```

For MacOS homebrew users, simply input the following into the macOS terminal:

```macos
brew install git
```

### Go

A dependency for Hugo-extended.

[Go documentation](https://go.dev/doc/)

For Windows scoop users, simply input the following in powershell:

```powershell
scoop install go
```

For MacOS homebrew users, simply input the following into the macOS terminal:

```macos
brew install go
```

### Hugo-extended

This is the framework used for our website, without which you cannot render your webpage locally.

> ❗ We are using [hugo-extended](https://gohugo.io/documentation/), not base hugo.

For Windows scoop users, simply input the following in powershell:

```powershell
scoop install hugo-extended
```

For MacOS homebrew users, simply input the following into the macOS terminal:

```macos
brew install hugo
```

After installation, check your version of hugo with (for both Windows and macOS):

```powershell
hugo version
```

Ensure that your version of hugo includes `+extended` after its hash:

![Screenshot of hugo-extended hash](/assets/media/hugo-extended-example.png)

### Nodejs

May be required for building the server on your local computer.

[Nodejs documentation](https://nodejs.org/en/docs/)

For Windows scoop users, simply input the following in powershell:

```powershell
scoop install nodejs
```

For MacOS homebrew users, simply input the following into the macOS terminal:

```macos
brew install node
```

### Confirm all packages are successfully installed

Use the `list` function for both package managers to identify all the software you have currently installed.

For Windows scoop users, simply input the following in powershell:

```powershell
scoop list
```

![Screenshot of scoop list](/static/uploads/scoop-list.png)

For MacOS homebrew users, simply input the following into the macOS terminal:

```macos
brew list
```

### Code Editors

This refers to software that allow you to edit code, usually with syntax highlighting.

I (Han Sheng) personally use [Visual Studio Code](https://code.visualstudio.com/).

Other options include:

- [Notepad++](https://notepad-plus-plus.org/downloads/)

### Git Graphical User Interface (GUI)

As our repositiory is hosted on GitHub, [GitHub Desktop](https://desktop.github.com/) would be less troublesome to set up.

Other GUIs such as [Sourcetree](https://www.sourcetreeapp.com/) may require additional user accounts to be created.