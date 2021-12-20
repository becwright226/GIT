# git push
When you have a [remote](./Remote.md) set up you'll need to start sending over your [commits](./Commit.md)to your remote. This can be done with th command git push.

You can attach a name and branch name to your command to specify where you are pushing to.

```
git push origin main
```

This command will push the *main* branch to the remote called *origin*. This means tat any commits that are in your local will be *pushed* to the remote.

### Upstream Tracking

Instead of including the name of the remote and the branch you're on everytime, you can set local branches to track an upstream branch. This means you can tell the branch to push to its assigned upstream remote branch by using the command `git push`.

Before doing so, you'll need to use the`-u`tag. THis can be done on any `git push`.

`git push -u origin main"

After this command is used, you can just use the `git push` and it will function the same.

-[Git push Documemntation](https://git-scm.com/docs/git-push)

---

[Back to Home](../README.md)