# git commit
The command `git commit` will take all tracked changes (items added [with git added](./Add.md)) and package them up in what is called a commit

Commits come with commit messages that are required for each commit. You add a messagfe to a commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

for example , if we have an application we're working on where we just built out the abulity to register new accounts, then you might have some variation of the following:
```
git add .
git commit -m "added register functionality"

then when viewing the history of the git repository, you can pinpoint wherethe registration funtionally was added 

## Resources
-[Git Commit Documenation](https://git-scm.com/docs/git-commit) 

---

[Back to home](../README.md)\


