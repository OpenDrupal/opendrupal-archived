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

2) Front End Development
------------------------

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

#### E. CSS Architecture & Standards

* __Read:__ SMACSS, BEM
* __Do:__ Write your own mini CSS styleguide, highlighting the most important parts to you. Save this as a .md file within a GitHub repository.

__Resources__

* Sass styleguides

#### F. Gulp & Advanced Sass (Optional)

* Install Node.js, Gulp & Libsass within your theme
* Add in browsersync & autoprefixer
* Look at yo-generator-webapp & Google's web starterkit
