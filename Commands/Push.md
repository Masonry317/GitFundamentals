# git push

when you have a [remote](/Remote.md) set up you"ll need to begin to move [commits](./COMMIT.md)to remote.
this can be done with the command `git push`

you can attach a name and branch name to your command to specify where your're pushing to

```
git push origin main
```

this command will push the ***main*** branch to the remote called **origin**. 
this means any commits that are in your local will be **pushed** to the remote.

### Upstream Tracking

Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch.
This means you can tell the branch to push to its assigned upstream remote branch by using the command `git push`.

Before doing so, you'll need to use `u` or `--set upstream` flag. this can be done on any `git push`. 

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will function the same way

- [git push](./commands/Push.md)