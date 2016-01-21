The Toolchain Continued & Site Building
=======================================

Deployment
----------

### A. Components of a website

The following components make up a Drupal site:

1. Codebase
2. Database
3. Files

Commonly a website will run on several environments, e.g local, dev, staging and production. We need to make sure we can effectively migrate our website between these environments. These techniques will also be useful for setting up websites locally.

### B. Methods of migrating between environments

1. PhpMyAdmin, Adminer, Backup & Migrate
2. Git repository for code - how to configure?
3. Settings.php
4. Files directory

### C. Process

* Make sure you understand the migration and deployment process
* Export all of the components of your site.
* Reset your VM - wiping everything - and re-import your site.

Git
---

### A. Git Basics

* __Do:__ https://try.github.io
* __Do:__ https://www.codecademy.com/learn/learn-git

### B. Setup Your Own Git Repo

* __Do:__ Initalise a new repository with your Blog site source code in.
* __Do:__ Sign up for free repository hosting (or loginto your account if you have one) on [GitHub](https://github.com/) or [BitBucket](https://bitbucket.org/) and push your code.
* __Do:__ Create a new branch, modify your codebase by downloading a new module, merge, add and push the code up.

### C. Git: Shared Repository Setup

####Group Activity 1

* Nominate one person to create a new git repo with a single text file in called ```changelog.md```. Now share this repo with everyone in the group.
* Now each member of the group should add in at least one new file and update the changelog with a new line
  ```file added [name] [date time]```
* Work on the repository collaboratively. If you encounter a merge conflict, open the file and resolve it using a text editor.

####Group Activity 2
* Work together as a group to draw a diagram explaning how git works based on what you have learned

###Checkpoint
* Create a blog post about Git. Include a screengrab and link to your blog repo and the diagram you created as a group.

### E. Gitflow (optional)

* __Read:__ [A successful branching model](http://nvie.com/posts/a-successful-git-branching-model/)
* __Do:__ Install the [Gitflow plugin](https://github.com/nvie/gitflow), create a feature branch on your blog site with some work on and merge into master via a release branch.
* __Do:__ Repeat the previous group excersises using gitflow

### Extra Resources

* [Pro Git](https://git-scm.com/doc)
* [Atlassian: Git](https://www.atlassian.com/git/)
* [Git - The Simple Guide](http://rogerdudler.github.io/git-guide/)
* [Git Immersion](http://gitimmersion.com/)


To Do
-----

* __Read:__ Pro Git, [chapter 1](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics) and [3.2: basic branching and merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).
* __Read:__ [Pro Git](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics), chapter 2, 3, & 4.
* __Read:__ [Github: Using pull requests](https://help.github.com/articles/using-pull-requests/).
* __Do:__ Create a new pull request on a repo.
