Project Setup & Intro to the Toolchain
======================================

Overview
--------
###Here is what we'll be covering:

1. Presentation and discussion of your project idea
2. Local development environments 
3. Introduction to command line
4. Drush - a command line shell and Unix scripting interface for Drupal

###By the end of this lesson you will:**

* Have decided on your project and documented the main requirements for it
* Set up your local development environment and be comfortable using it
* Have experience using the command line & Drush to download and install Drupal 8 and some modules

1) Project Review
-----------------

Present your project idea to the group, let us know what you are thinking of building, who the site is aimed at roughly how you see it working and what modules you are thinking of using. Following each presentation will be a group discussion about your project, a chance for everyone else to feedback on your ideas, ask questions and make suggestions. Appoint a different person for each presentation to keep track of the discussion and record the main points.

Now, do the following:

* __Do:__ Write up your project plan and include: a summary of the site, the main pages, key Drupal modules, advanced functionality.
* __Checkpoint:__ rename your Google Doc to "Full Project Plan" and save it in a folder called *"Open Drupal - [name]"* replacing [name] with your full name. Now share this folder with the trainer.

2) Local Development Environment Setup
--------------------------------------

Group discussion / showcase of your current local dev set up(?)

@todo - Discuss VM 
- do we need an update?
- some firms/candidates have their own 

* __Do:__ Open Drupal VM tutorial, *Tutorials->open_drupal_vm.md*
* Now set up a snapshot at your machine's vanilla state.
* __Checkpoint:__ all have a working local environment and be able to edit our Drupal sites.
* __Group discussion:__ Q&A on virtual machines and local setup, tips & tricks on local development.

3) Command Line
---------------
The command line & Drush while not essential tools are widely used and can make you more efficient and grant access to more powerful system features. For example, think about the time it would take you to find, download and install 5 separate modules. Not a great deal of time, granted, yet a fair bit more time than it takes with Drush:

```
drush dl module1 module2 module3 module4 module5
drush en module1 module2 module3 module4 module5
```

### A. Command Line Basics

* __Do:__ [CodeAcademy - Learn the Command Line (units 1 & 2)](https://www.codecademy.com/learn/learn-the-command-line).

### B. VIM (optional)

* __Do:__ [Open VIM Tutorial](http://www.openvim.com/tutorial.html).
* __Do:__ Create a new blog post with an outline of how to use the command line and links to resources.

### Extra Resources

* [*NIX Spellbook](http://nixsrv.com/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)

4) Drush
--------

### A. Drush Intro

* __Read:__ [DigitalOcean - A beginners guide to Drush](https://www.digitalocean.com/community/tutorials/a-beginner-s-guide-to-drush-the-drupal-shell)
* __Do:__ Download a module using Drush, then enable it. Then check your Drupal site for updates and install any
* __Do:__ Write your own Drush cheatsheet with at least 10 useful commands.
* __Checkpoint:__ Save your Drush cheatsheet in your folder.

### B. Drush Aliases (optional)

* __Read:__ [Deeson: Drush aliases](https://www.deeson.co.uk/labs/drupal-drush-aliases-and-how-use-them)
* __Read:__ [example.aliases.drushrc.php](https://github.com/drush-ops/drush/blob/master/examples/example.aliases.drushrc.php)
* __Do:__ Create an alias to your local Drupal installation. Set up a site on a remote environment and set up an aliases for this site.

### Extra Resources

* [Drushcommands.com](http://drushcommands.com/)
* [Github.com/drush-ops/drush](http://drush.ws/)
* [Drush docs](http://docs.drush.org/)

To Do
-----
* __Do:__ [Shortcut Foo - The command line](https://www.shortcutfoo.com/app/dojos/command-line). Complete level 1 & 2.
* __Do:__ [Learn code the hard way - The command line crash course](http://cli.learncodethehardway.org/book/), and practice.