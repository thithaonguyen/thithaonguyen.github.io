## Thao Nguyen blog setup

### Prerequisite

- Hugo
- Git

### Development

In VSCode terminal, run command `hugo server -D`. Then open browser and go to `http:://localhost:1313` to preview.

Make changes in `/content` and and live preview in the browser.

### Commit change


When you are done with edit, press Ctrl + c to terminate Hugo then commit changes to git using the following commands:

`git add .`

`git commit -m "{commit_message}"`

Note that: Now all changes are saved to git, but the new content is only available in local laptop.
To update the website on github, follow the next step to make it available on github.

### Publish change to Github

To publish to github, run the command

`git push`