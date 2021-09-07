# Git Remote

when working with git , a **remote** is a git repository that is not on the machine you're working on.

Take GitHub for example. while git is the technology that allows you to create local repoositories, GitHub is the site that will host your remote repositories. Once stored remotley, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared bweteen the two. 


### Adding a remote 


A remote can be added with the `git remote add` command, followed by the same and location of the remote 

the name is a local name, meaning its your label and does not impact the actually remaote whatsoever 

```
git remote add orgin (https://github.com/ElevenfiftyAcademy/GitFundamentals.git)
```

### Removing a remote 
A remote can be removed with `git remote remove` command , followed by the name of the remote.

```
git remote remove origin
```

## Resources 

- [Git Remote Documentation](https://git-scm.com/docs/git-remote) 
---
[Back to home](../README.md)

