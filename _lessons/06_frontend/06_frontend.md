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

Start to theme your Drupal site by creating new Sass partial files.

### D. BEM, SMACSS & CEMS (Optional)

* http://markrabey.com/2014/11/07/writing-good-css/

### Extra Resources

* [Dive Into HTML5](http://diveintohtml5.info/index.html)
* [HTML5 Rocks](http://www.html5rocks.com/en/)
* [Smashing Magazine: HTML](http://www.smashingmagazine.com/tag/html/)
* [Drupal CSS Coding Standards](https://www.drupal.org/coding-standards/css)
