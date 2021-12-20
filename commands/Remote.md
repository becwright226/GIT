# Git Remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. Te counterpart to this is **local** , or the machine that is being developed on.

Take GitHub for eample. While git is the technology that allows you to create local repositoroes, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote
A remote can be added with the git remote add command, followed by name and location of remote.
The name is a local name, meaning it is your label and does not impact the actual remote whatsoever.
git remote add origin https://github.com/becwright226/GITFUNDAMENTALS.git

### Removing a remote
A remote can be removed with the git remote remove command, followed by the name of the remote.
git remote remove origin

## Resources

-[Git Remote Documemntation](https://git-scm.com/docs/git-remote)

---

[Back to Home](../README.md)

### Git Commands
[git commit](./commands/Commit.md)
[git init](./commands/Init.md)
[git add](./commands/Add.md)
[git remote](./commands/Remote.md)
[git config](./commands/Config.md)