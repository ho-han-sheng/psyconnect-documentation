---
title: Hosting Local Web Server
linktitle: Hosting Local Web Server
type: book
date: '2023-01-07T00:00:00+08:00'
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 40
---

Congratulations! You've finished editing and can now view the fruits of your labour. In order to check if your code is workable and the possible visual changes on the website, you need to deploy a local webserver hosting your offline copy of our website.

To do this on VSCode:

1. Ensure all your changes in open editors are saved using the `File/Save` button on the top left or the `Ctrl+S` keyboard shortcut. You should see your edited file highlighted with either an `M` or a `U` for modified and uploaded respectively.

![Screenshot of modified file](modifed-example.png)

![Screenshot of uploaded file](uploaded-example.png)

2. Open up VSCode Terminal with the `Terminal` tab.

![Screenshot of terminal tab](new-terminal-1.png)

3. A new terminal will show up at the bottom of VSCode.

![Screenshot of terminal](new-terminal-2.png)

4. Type in `hugo server` to deploy the website.

![Screenshot of terminal](new-terminal-3.png)

5. The resulting response may be too large for your current window so expand it if you have to. You should receive something similar to the below picture.

![Screenshot of terminal](new-terminal-4.png)

6. Following the last line of the response, open up any web browser and type in `http://localhost:1313/` (or whatever url the response mentions). You should be able to interact with and view your local changes to the website.

![Screenshot of terminal](localhost.png)

7. Check your changes and ensure that nothing else is unintentionally affected. Use `Ctrl+C` in the same VSCode terminal to stop your web server and continue making edits if you have to. Redeploy the website locally to check your edits again.

Once you are satisfied with your changes, you can now move on to making a commit.
