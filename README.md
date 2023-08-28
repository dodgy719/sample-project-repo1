# Data Science: Sample Group Project Structure

## Key Takeaways

1. All individual work should be done within your personal "group member" folder.
2. All individual work should be done on your personal "group member" git branch.
3. Communication is key! Working on the same jupyter notebook at the same time will likely result in a merge conflict.
4. Don't Panic! A merge conflict is not the end of the world - let an instructor know, and we will help you fix things up.

## Directory Structure

For this project we suggest the following directory structure:

```
project-folder
    ├── data-folder
    ├── images-folder
    ├── notebooks-folder
    |   |
    |   ├── group-member-1-notebooks-folder
    |   |   |
    |   |   └──group-member-1-working-notebook.ipynb
    |   |
    |   ├── group-member-2-notebooks-folder
    |   |   |
    |   |   └──group-member-2-working-notebook.ipynb
    |   |
    |   └── group-member-3-notebooks-folder
    |       |
    |       └──group-member-3-working-notebook.ipynb
    |
    ├── README.md
    ├── report-notebook.ipynb
    └── presentation.pdf
```

The goal here is that you are working only in your own folder. Never add/commit files that are in another member's folder!

## Git/GitHub Workflow

For this project, we suggest the following Git/GitHub workflow (a branching workflow):

![branching structure diagram](images/git-branches-diagram.png)

The goal here is that you're working on your own branch. We recommend naming each branch after the group member.

The workflow should look like the following:

1. Clone the most repo from the remote `main` branch. -> Only do this once

Repeat the following steps as needed:

1. Move to your working branch locally: `git checkout <name of member branch>`
2. Do the work! Make changes and edits to your project content!
3. Add and commit changes to your branch: `git add <file name>` then `git commit -m 'Meaningful message describing changes to be committed'`
4. Push changes to your remote working branch: `git push origin <name of member branch>`