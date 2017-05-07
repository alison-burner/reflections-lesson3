
# When would you want to use a remote repository rather than keeping all your work local?

You might want to use a remote repository for the following reasons:

* Github provides free storage when you host a public repository. This allows for a built-in back-up that you do not maintain.
* If there are multiple collaborators working on the same project, a remote repository can act as the home base of the most recent version that people can collaborate on.
* If you use multiple machines, you won't need to worry about getting access to another machine's storage.


# Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?

You may not want to automatically update your local copy if you are working on a commit; you may not want to update your remote without notifying other collaborators. It also encourages the user to stay up-to-date with happenings on the remote even if they are not directly interacting with it.

# Describe the differences between forks, clones, and branches. When would you use one instead of another?

* Forks: Cloning a repository on Github to another repository on Github. Your copy has a link back to the original repository.
* Clone: Copying the contents of a repository onto your local machine or Github. The difference between forks and clones in that you can clone anywhere, but you can only fork a repo on Github.
* Branches: Rather than creating an entirely new version of a repo, whether yours or another's, you can create a copy focused on a new feature which will eventually merge back into the master repo. Forks and clones may not ever merge into the master repo. 
