User Stories and Planning
=========================

Overview
--------
###Here is what we'll be covering:

1. Presentation and discussion of your project idea
2. Personas - the types of user who might use your site
3. Recap user stories and estimation 
4. Initial documentation for your project

###By the end of this lesson you will:**

* Have decided on your project and documented the main requirements for it
* Have developed your own user stories with estimations for your project


1) Project Review
-----------------
###Group activity
Present your project idea to the group, let us know what you are thinking of building, who the site is aimed at roughly how you see it working and what modules you are thinking of using. Following each presentation will be a group discussion about your project, a chance for everyone else to feedback on your ideas, ask questions and make suggestions. Appoint a different person for each presentation to keep track of the discussion and record the main points.

### Section Checkpoint

* __Do:__ Write up your project idea as a document saving it to your folder on Google Drive. Include:
..* A summary of the site
..* The main pages
..* Key Drupal modules
..* Advanced functionality you may include 

2) Personas
-----------
Who are the main types of people who will be using your site? We need to know a bit about these users, or groups of users before we can write the story cards. Obviously there will be a main admin user with top level permissions and access but there may be extra admin users to perform special functions too. There will be anonymous users as well - people who have never visited the site before or have not yet signed in but maybe some other groups in between? Here are some examples of user groups and what they might need to do:

###Example
A website for a medium sized company with pages, news items, and contact forms for different departments. They also have a blog section with content provided by members of the public.

* Blogger
..* Create and publish own blog posts
..* See own unpublished blog posts
* Blog Editor
..* Edit, promote, delete all blog posts
..* See all unpublished blog posts
* Press Officer 
..* Create/edit/delete news items
..* See all unpublished news items
..* Schedule News items for future publication
* Site Editor
..* Create/edit/delete pages and webforms
..* See all unpublished content
* User Administrator
..* Grant/revoke user roles
..* Add new users

### Section Checkpoint
* __Do:__ Create a list of the main user groups for your project and the tasks they would want to do - add this to your project documentation.

3) User Stories & Estimates
---------------------------
###Group Activity
Work in pairs or groups of three to come up with at least 10 user stories for your project using the standard structure:

*title
*actor
*narrative
*goal

####Example
|Actor: |As a |journalist|
|Narrative: |I want to |see contact information relating to the news article I am reading|
|Goal: |So that	|I can get directly in touch with the press office about it|

Once you have 10 or so story cards agree on an estimate using numbers 1-5 or T-shirt sizing.

### Section Checkpoint
* __Do:__ Create a spreadsheet of all the user stories for your project based on the template provided.


4) Session Checkpoint
---------------------
* __Do:__ Create a blogpost outlining the day's session linking to your new documentation.

To Do
-----
###Before next time:
* __Read:__ [Gov.uk 'writing user stories'](https://www.gov.uk/service-manual/agile/writing-user-stories.html)
* __Do:__ Add more user stories to your spreadsheet.















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