# WordPress Developer Coding Assignment
The challenges below will test your familiarity with some of the WordPress basic functionalities like shortcodes, settings pages, metaboxes, storing custom data for posts, retrieving data from the database.

## Requirements:
We use Local By Flywheel as our development tool. Please use it to complete these challenges.
Once you are done, right-click the local site in Local by Flywheel and create an export. Send said export to us for review.

## Challenge: Slideshow Plugin
This plugin will test if you are familiar with WordPress shortcodes.

### Admin-Side:
* Create an admin-side settings page.
* Provide an interface to add/remove images from plugin settings page.
* User must be able to change order of uploaded image. (Hint: Use http://jqueryui.com/demos/sortable/#connect-lists )

### Front-end:
* Create provision for a shortcode like [myslideshow]
* When you add shortcode [myslideshow] to any page, it will be replaced by a slideshow of images uploaded from admin-side.
* Our prefered slider library is: https://kenwheeler.github.io/slick/
* You can use the library either by downloading and including it in the project or as an npm package.

## Challenge: Contributors Plugin
This plugin will test if you are familiar with WordPress metabox functionality. Goal is to create a plugin so that we can display more than one author-name on a post.

### Admin-Side:
* Add a new metabox, labeled "contributors" to WordPress post-editor page.
* This metabox will display list of authors (wordpress users) with a checkbox for each author.
* User (author/editor/admin) may tick one or more authors name from the list.
* When post saves, states of checkboxes for author-list in "contributors" box must be saved as well.

### Front-end:
* At the end of post, display a box called "Contributors".
* It will have list of authors checked for that post.
* Show contributor names with their Gravatars.
* Contributor-names must be clickable and will link to their respective "author" page.