# git remote

When working with git, a **remote** is any get repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine is being developed on.

Take Github for example. While git is the technology that allws you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note** : While the repositories (loacal and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the same remote.

```
git remote remove origin
```

##Resources

-[Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)
