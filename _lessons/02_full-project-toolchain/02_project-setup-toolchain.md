Project Setup & Intro to the Toolchain
======================================

Overview
--------

* Deciding on a project to work on over the coming workshops, so there is a consistent focus and so you can build something useful and use as evidence.
* Setting up and making sure we're comfortable with our local development environments, so when we use this environments in the future we know what we're doing.
* Using the command line & Drush, as they are widely used developer tools and can make you quicker and access more powerful system features.

1) Project Set Up
-----------------

### A. Decide on a project

Think about a project you're interested in creating. Look through the [project examples](https://drive.google.com/drive/u/1/folders/0BzS3s9jPn08-V3NkQ0Z1RzNaMU0/0ByiysEQCBIteU3Q4eU1JT01PcEU/0By9KqisVw_3lTnRSZnVPb2RIMjA) and use these as suggestions for the types of project you could create.

Your project must include the following:

* It should be focused around content you'll add yourself, and have a section listing this content in some way.
* It should accept and process user input in some way.
* It should be something realistic and suitable for Drupal.
* Any advanced functionality should be documented in a separate part of your plan.
* The project must be started from scratch, so no distributions or existing websites you've built.

Now, do the following:

* __Do:__ Write up your project plan and include: a summary of the site, the main pages, key Drupal modules, advanced functionality.
* __Checkpoint:__ rename your Google Doc to "Full Project Plan" and save it in a folder called *"Open Drupal - [name]"* replacing [name] with your full name. Now share this folder with the trainer.

### B. Local Development Environment Setup

* __Do:__ Open Drupal VM tutorial, *Tutorials->open_drupal_vm.md*
* Now set up a snapshot at your machine's vanilla state.
* __Checkpoint:__ all have a working local environment and be able to edit our Drupal sites.
* __Group discussion:__ Q&A on virtual machines and local setup, tips & tricks on local development.

2) Command Line
---------------

### A. Command Line Basics

* __Read:__ [CodeAcademy - getting comfortable in the terminal](http://www.codecademy.com/blog/72-getting-comfortable-in-the-terminal-linux).
* __Do:__ [Learn code the hard way - The command line crash course](http://cli.learncodethehardway.org/book/), and practice.

### B. Test

* __Do:__ [Shortcut Foo - The command line](https://www.shortcutfoo.com/app/dojos/command-line). Complete level 1 & 2.

### C. VIM (optional)

* __Do:__ [Open VIM Tutorial](http://www.openvim.com/tutorial.html).
* __Do:__ Create a new document and write an outline of how to use the command line.
* __Checkpoint:__ Save this document in your folder and call it '01_command_line.txt'.

### Extra Resources

* [*NIX Spellbook](http://nixsrv.com/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)

3) Drush
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
