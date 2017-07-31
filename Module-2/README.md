# Git-101: An Introduction to Git using SourceTree

## Module 2: Adding and Staging Changes

In this module we will add a readme file that has some generic text, we will then stage those changes to get ready for committing and pushing them in the next module. Staging files allows us to have a simple workflow within the repository. 

The basic GIT workflow is as follows: Create repository -> **create or copy over files -> stage them to be saved at their current state** -> commit them -> share the commit with your team -> work on new ideas or sections of the project -> merge them back with the original branch -> repeat.

### Creating and Staging Files within Git

In this tutorial we create a readme file and stage it within our local Git repository.

1. Within SourceTree click on Open in Explorer to open the directory of the newly created repository.
1. Right click within the explorer window and create a new Text Document.
1. Name the file `readme.md`.  The .md extension is for Markdown Text. This is a simple, easy to use, flat text file format. *If you are unfamiliar with Markdown I highly suggest you check it ([here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)) out as this entire tutorial was written in markdown.*
1. Open the newly created file and type the following text below.

```markdown
# Readme for Git-101

Hello!
```

1. Save the file and close it. Head back to SourceTree.
1. Stage the newly created file by selecting it and and selecting Stage Selected. *Note the file's contents appear in the right pane of SourceTree.  If you had any changes to an already committed file you would see a diff (or the changes) of that file.*

![Create and Add File](./images/createAndAddFile.gif)

[Continue on to Module 3](./Module-3)

## Table of Contents

1. [Module 0: Setup Git, SourceTree, and Github](./Module-0)
1. [Module 1: Create a new Repository](./Module-1)
1. [Module 2: Adding and Staging Changes](./Module-2)
1. [Module 3: Committing and Sharing Changes (*Pushing*)](./Module-3)
1. [Module 4: Branching, Merging, and Reverting](./Module-4)
1. [Module 5: Cloning and Forking](./Module-5)