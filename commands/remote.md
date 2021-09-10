# git remote 

When working with git, a **remote** is any git repository that is not on your machine you're working on. the counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the thecnology that allows you to create local repositories, GitHub is the site that will host remote repositories. once stored remotely you can bring that repository back down or share with others.

**Note**: While the repositories (local or remote) are tracking the same project, they can have different states if changes are not shared between the two.

## Adding a remote

A remote can be added with the 'git remote add' command, followed by the name and location of the remote. 

The name is a local name, meaning it's your label and does not impact the remote whatsoever.

'''
git remote add origen https://github.com/elevenfiftyAcademy/GitFundamentals.git
'''

## Removing a remote 

A remote can be removed with the 'git remote remove' command, followed by the name of the remote.

'''
git remote remove origen
'''

## Resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

- [Back to home](../README.md)