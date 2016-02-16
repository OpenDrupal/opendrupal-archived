

### D. Kanban & Design in Agile 

* [Kanban](https://www.atlassian.com/agile/kanban)
* [Design Spikes](http://www.smashingmagazine.com/2012/11/06/design-spikes-fit-big-picture-ux-agile-development/)

Project Management Systems
--------------------------

Project management systems are essential to any successful project. You'll need to

### A. Types of system

* Trello
* GitHub issue queue. See [mastering issues](https://guides.github.com/features/issues/).
* JIRA
* Open Atrium
* Real life board

* __Do:__ Sign-up for one of these systems (we recommend Trello) and add all your user stories to a 'backlog' section in a kanban board.
* Use this management system as you proceed to develop your site.

* __Checkpoint:__ Take a screenshot of your PM system, and include it in a blog post explaining the process you'll be undertaking.

### B. Build a scrum board (optional)

* Using post-it notes build a real life scrum board.





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



The Toolchain Continued & Site Building
---------------------------------------

### Preparation

* @todo

### What we'll cover today:

* Recap the previous workshop
* Start adding some modules and configuration to our sites
* Git basics
* Set up a repository and add our codebase
* Learn about deployment techniques between environments

Project Build
--------------

* Recap previous workshop: quiz on command line commands & Drush commands.
* Review project plans & update if needed.

### A. Start building your site

30 Minutes - 1 Hour

Git
===

* __Group Discussion:__ What is version control and why do we need it?

Deployment
==========

* __Group Discussion:__ The deployment process.
* __Group Discussion:__ Environments & web servers.
* __Do:__ Write down the different components you need to think about when deploying or migrating sites and what we need to consider about them.



Site Building & Front End Development
=====================================


Overview
--------

A look into the Drupal contrib module ecosystem, install some useful modules to assist with development and dive deeper into a few powerful modules relevant to your project. Then spend some time going over the frontend development landscape and start building a theme in Drupal, learning about subtheming and getting started with Sass.

After this lesson you should have:

* A better understanding of contrib modules
* Configured an advanced module for your site
* A Drupal subtheme based on a popular base theme
* Customised your subtheme with a template
* A custom stylesheet and a understanding of how to implement CSS within Drupal
* Sass and Compass up and running on your local development environment

1) Modules
----------

### A. The Module Ecosystem

* __Read:__ [Drupal.org: Assessing modules](https://www.drupal.org/node/1585732)
* __Read:__ [Acquia: Evaluating Modules pt 2](https://www.acquia.com/gb/blog/selecting-drupal-modules-part-2-searching-modules)
* __Read:__ [Acquia: Evaluating Modules pt 3](https://www.acquia.com/gb/blog/how-select-drupal-modules-part-3-evaluation-tips)
* __Read:__ [6 Modules to Avoid Before Drupal 8 Arrives](https://www.ostraining.com/blog/drupal/modules-avoid-drupal-8/)

### B. Standard Development Module Stack

* Make sure you have the following useful stack of modules and dev tools installed: Views, Admin Menu, Adminimal Administration Menu, Devel, Link, Webform, Backup & Migrate, Diff, Features, Libraries, jQuery Update, Maillog, Masquerade, Module Filter, Fast Permissions Administration, Pathauto, Token.
* Take a look at the module pages of any modules you haven't heard of and read up on what they do.

* __Hint:__ ```drush dl views admin_menu adminimal_admin_menu devel link webform backup_migrate diff features libraries jquery_update maillog masquerade module_filter fpa pathauto token```

### C. Selecting & Configuring Advanced Modules

* __Do:__ Which modules are relevant to your site? Take some time to pick a few, some popular modules you might want to consider include: Views, Date, Display Suite, Context, Panels, CKEditor, Media, File Entity.
* __Do:__ Drill down into one or two module and read up on their documentation. Views, Display Suite and Panels are very powerful modules and worth spending the time to understand in more depth.

#### Views

* __Do:__ configure Views, Display Suite & Date for your site to show a list of date based content (e.g blog posts, events) which can be filtered by a URL string using contextual filters. Try creating a navigation block showing a summary of these dates. (Hint: take a look at the 'archive' default view).

* @todo - Add resources & instructions for advanced configuration of Views, DS & Panels.

2) Front End Development and Drupal
-----------------------------------

### A. Overview

* __Read:__ [Front-end Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)
* __Read latest editions / subscribe:__
  * [Front end Rapport: Lullabot](http://tinyletter.com/front-end-rapport/archive)
  * [Responsive Design Weekly](http://responsivedesignweekly.com/)
  * [Hugo Giraudel's Blog](http://hugogiraudel.com/blog/)
  * [Javascript Weekly](http://javascriptweekly.com/)

### B. Drupal Theming

### A. Types of Themes

* __Research:__ Find out what the differences between a 'base theme', 'sub theme' and 'starter-kit' are in Drupal. What components does a sub theme inherit from a base theme?
* __Hint:__ Here's a [good discussion on drupal.org](https://www.drupal.org/node/2474021).

### B. Evaluating Themes

* __Read:__ [DrupalCon Munich 2012: Evaluating Base Themes](http://munich2012.drupal.org/sites/default/files/slides/basethemes-handout-munich_2.pdf)
* __Read:__ [Drupal Base Themes](http://friendlymachine.net/posts/2012/drupal-base-themes)

### C. Working with Themes

* __Watch:__ [Drupallize.me Introduction to Advanced Theming](https://drupalize.me/videos/introduction-advanced-theming-drupal-7?p=1146)

Two of the most popular base themes for major custom Drupal projects are [Zen](https://www.drupal.org/project/zen) and [Omega version 4.x](https://www.drupal.org/project/omega) - decide one to install and create a sub theme from:

#### Zen

* [Drupal.org: Create a Zen Subtheme](https://www.drupal.org/node/873778)
* [YouTube: Creating Responsive Drupal Sites with Zen Grids and the Zen 5 Theme](https://www.youtube.com/watch?v=_4xdymhPiVQ)

#### Omega

Note: Omega 4.x is fairly complex and can be challenging for beginners, it is however very powerful.

* [Omega: Creating a subtheme](https://www.drupal.org/node/1936948)
* [Beginning Drupal 7 Theming with Omega](http://radarearth.com/content/beginning-drupal-7-theming-omega)

#### Other Themes

Some other base themes worth considering:

* [Gesso](https://www.drupal.org/project/gesso)
* [Aurora](https://www.drupal.org/project/aurora)
* [Mothership](https://www.drupal.org/project/mothership)
* [Bootstrap](https://www.drupal.org/project/bootstrap)

### C. Front End Tools

* Getting tooled up, other front end technologies you might need to know about (Grunt, Gulp, Sass etc).
* Grunt / Gulp / Ruby / any other technologies required
* Building things the right way - look through documentation, keep things clean etc.

3) CSS & Sass
-------------

#### A. CSS

CSS is a huge topic in itself. It's vital to understand CSS deeply for effective front end development.

#### B. Sass & Compass

* __Do:__ Install [Ruby & Sass](http://sass-lang.com/install) via the command line.
* __Read:__ [Intro to Sass](http://sass-lang.com/guide).
* __Do:__ Install [Compass](http://compass-style.org/install/) via the command line.
* __Read:__ [Intro to Compass](http://compass-style.org/help/)
* __Do:__ Navigate to your sub theme and run ```compass watch``` to compile your stylesheets.
* __Do:__ Start theming your site, aim to target one content type at first.

#### C. Sass Plugins

* Breakpoint, Singularity, Susy, Zen Grids.

#### E. CSS Architecture & Standards (Optional)

* __Read:__ SMACSS, BEM
* __Do:__ Write your own mini CSS styleguide, highlighting the most important parts to you. Save this as a .md file within a GitHub repository.

#### F. Gulp & Advanced Sass (Optional)

* Install Node.js, Gulp & Libsass within your theme
* Add in BrowserSync & Autoprefixer
* Look at yo-generator-webapp & Google's web starterkit

Site Building & Front End Development
=====================================

1) Modules
----------

Quick run through: 1 - 2 hours

### A. The Module Ecosystem

* Read through articles and write down your own 3 top tips for evaluating and selecting modules.
* Group discussion on the top tips.

### B. Development Module Stack

* Group discussion: which modules do you commonly use?

### C. Selecting & Configuring Advanced Modules

* Group discussion: which modules did you decide on?
* Demos: how to use some of the more popular modules. Tips & tricks on using modules.

2) Front End Development
------------------------

### B. Drupal Theming

Trainer note: depending on ability and progression, get everyone to decide on one theme and walk through installation and toolset installation. Get to the most basic point of editing a line of Sass.

Write down advantages / disadvantages of popular themes


Frontend Development & Theming in Drupal
========================================

HTML & Templating
-----------------

Aims: Be able to write well structured, semantic HTML. Understand Drupal's theme system, override template and theme functions.

### A. HTML 5

* __Do:__ Using the following resources as a references points, write a blog post on a) What is HTML5? b) Why are semantics in HTML important.

__Resources:__

* [Dive Into HTML5: Intro](http://diveintohtml5.info/introduction.html)
* [Dive Into HTML5: Semantics](http://diveintohtml5.info/semantics.html)
* [MDN HTML Element Reference](https://developer.mozilla.org/en/docs/Web/HTML/Element)
* [HTML5 Doctor: Let's talk about semantics](http://html5doctor.com/lets-talk-about-semantics/)

### B. Templates

* __Read:__ [Overview of theme files](https://www.drupal.org/node/171194)
* __Read:__ [Drupal 7 Template Suggestions](https://www.drupal.org/node/1089656)

* Create a new template override for a custom block which is placed in a sidebar region, add a custom wrapper class and use the relevant HTML5 element.

* Now, try adding custom template overrides for:

1. A specific region
2. Your site's front page
3. page.tpl.php based on content type

Make sure you update any HTML to use the semantically correct elements.

### C. Customising Themes

* Add a new region to your theme by declaring it in THEMENAME.info and adding it to page.tpl.php

### E. Theme Overrides

To override HTML output in Drupal as well as using templates we can also use theme functions. These include preprocess, process and theme functions.

Read the following articles and implement [template_preprocess_page()](https://api.drupal.org/api/drupal/includes%21theme.inc/function/template_preprocess_page/7) to add a string (e.g "Hello World!") to a page.tpl.php file in your custom theme.

* __Read:__ [Beginners guide to overriding themable output](https://www.drupal.org/node/457740)
* __Read:__ [Finding Variables](http://themery.com/dgd7/advanced-theming/finding-variables)
* __Read:__ [Preprocess & Process Functions](http://themery.com/dgd7/advanced-theming/preprocess-process) + part [2](http://themery.com/dgd7/advanced-theming/preprocess-process/implement), [3](http://themery.com/dgd7/advanced-theming/preprocess-process/variables) and [4](http://themery.com/dgd7/advanced-theming/preprocess-process/in-action)

Also try:

1. Implementing [template_preprocess_node](https://api.drupal.org/api/drupal/modules!node!node.module/function/template_preprocess_node/7) to add custom variables for specific content types.
2. Implement [theme_breadcrumb](https://api.drupal.org/api/drupal/includes%21theme.inc/function/theme_breadcrumb/7) to change the separator between breadcrumb items.
3. For other ideas see the [CEMS base theme's includes folder](https://github.com/hedleysmith/CEMS/tree/master/includes).

CSS, Sass & Styling Drupal
--------------------------

Aims: Be able to write well structured and consistently formatted CSS. Use the common features of Sass and apply them to a Drupal theme.

### A. CSS

Using the following resources as inspiration, come up with your own short CSS guidelines on writing well formatted CSS. Add it as a new project in your public GitHub account.

As a minimum this style guide should show one annotated example of a well written CSS rule and one annotated example of a badly written CSS rule.

* https://github.com/necolas/idiomatic-css
* http://cssguidelin.es/
* https://css-tricks.com/css-style-guides/
* http://sass-guidelin.es/

### C. Styling in Drupal

NOTES
=====

Start to theme your Drupal site by creating new Sass partial files.

### D. BEM, SMACSS & CEMS (Optional)

* http://markrabey.com/2014/11/07/writing-good-css/

### Extra Resources

* [Dive Into HTML5](http://diveintohtml5.info/index.html)
* [HTML5 Rocks](http://www.html5rocks.com/en/)
* [Smashing Magazine: HTML](http://www.smashingmagazine.com/tag/html/)
* [Drupal CSS Coding Standards](https://www.drupal.org/coding-standards/css)
1. Set up our systems, including installation of Sass and Ruby.

### A. HTML 5 

* Discuss HTML5
* Do exercise
* Discuss blog posts


