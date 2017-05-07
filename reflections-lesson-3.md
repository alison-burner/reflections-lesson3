
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


# What is the benefit of having a copy of the last known state of the remote stored locally?

The benefit is that you can always revert to the previous state if you are offline. Therefore, you don't need internet access to fix a bug.


# How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?

If you didn't collaborate with Git or Github, you'd need a pretty expensive cloud to store every version of your projects. You would not be able to collaborate at the same time to the extent you can in Git(hub). While it would be great to have a real-time repository like Google Docs for code, code requires more attention to detail. If file names are the same, it'd be extra difficult to sort through possibly thousands of files and directories -- you'd need to develop an organizational system that probably replicates Github.

# When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have?

You'd want to make changes in a separate branch if working on a specific feature -- especially if it's a project with only one collaborator. It can help with organization by clearly labelling everything in-process and also by dividing them into seperate files so as to avoid conflict. 

You'd want to make changes to Master if it's a change you feel is permanent, or that all collaborators will use. You would certainly make changes to Master if you're publishing a new version of software.