When would you want to use a remote repository
  rather than keeping all your work local?
* When I'm working on a project with someone else, or with a team
* When I want to have an online backup of my project
* When I want to share the source of my project with others

Why might you want to always pull changes manually rather than having
  Git automatically stay up-to-date with your remote repository?
* Because I might haven't completed the work on a fix or a feature,
  which might make the project broke and others won't be able to launch it.

Describe the differences between forks, clones, and branches.
  When would you use one instead of another?
* Forks are GitHub clones that have a reference to the cloned repository
* Clones a copy of a repository with its Git history
* Branches are like labels to commits

What is the benefit of having a copy of the last known state of
  the remote stored locally?
* This enables us to know the sync status of the local and remote branch if
  we ran offline. And also could allow us to merge offline too.

How would you collaborate without using Git or GitHub?
  What would be easier, and what would be harder?
* Without GitHub I'll need to communicate directly with other collaborators
  when I make some changes. But with GitHub I can just make a pull request,
  and all of the collaborators will be notified and can make their comments
  on it. And we can even discuss it from there!

When would you want to make changes in a separate branch
  rather than directly in master? What benefits does each approach have?
* When I think that some changes need to be approved by other collaborators,
  so that I can make a pull request before merging directly.
* When there are some development changes and I don't want to them to be
  directly in master to avoid bugs.
* But making a changes directly to master when there are some minor changes
  saves time and steps needed by pull requests.
