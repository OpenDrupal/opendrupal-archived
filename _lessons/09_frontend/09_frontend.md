Frontend Development
====================

1) JavaScript in Drupal
-----------------------

Aims:

### A. Adding JavaScript to Drupal

* __Read:__ [Drupal Behaviors Quick How To](http://www.amazeelabs.com/en/blog/drupal-behaviors-quick-how)
* For a good example of adding JavaScript to Drupal see [Omega's starterkit .js file](http://cgit.drupalcode.org/omega/tree/omega/starterkits/default/js/%7b%7b%20THEME%20SANITIZED%20%7d%7d.behaviors.js)
* __Do:__ Add a new custom behavior to your homepage that scrolls the window down when a user clicks a button at the top of the page.
* __Do:__ Try adding some more custom behaviors to

### B. Passing data from Drupal to JavaScript via Drupal.settings (optional)

* __Read:__ [The Drupal JavaScript API | Drupal.org](https://www.drupal.org/node/304258#drupal-settings)
* __Do:__ Create a block with three tabs called 'Welcome', 'Latest News' and 'Highlights'. If the current user has the role 'new user' select the 'Highlights' tab by default, if they have the role 'returning user' and if they have neither role show the 'Welcome' tab. To do this you'll need to create a custom module that adds the current user's roles to Drupal.settings and you'll then need to create a custom JavaScript behavior to switch tabs depending on the user's role. You'll also need to create some dummy user's!

### C. Debugging JavaScript in Drupal (optional)

* __Read:__ Read up on Chrome DevTools
* __Read:__ [Understanding JavaScript Behaviors in Drupal](https://www.lullabot.com/articles/understanding-javascript-behaviors-in-drupal)
* __Do:__ Put a breakpoint in Drupal's core Drupal.AttachBehaviors and step through
the render chain.

2) AJAX in Drupal (Optional)
----------------------------

### A. The AJAX API

* @todo

### B. cTools AJAX API

* @todo

### C. AJAX Forms

* @todo
