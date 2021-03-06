LRW Theme base
==============

WordPress Theme base to start projects. This is a project based entirely on ([Odin Framework](http://wpod.in/)), theme developed by [WordPress Brasil Group](https://www.facebook.com/groups/wordpress.brasil).

<h2>Description</h2>

A WordPress Theme base to assist in developing personal projects.  I added some basic functions for the projects that I develop with the agency and through freelancers:

* Add [Font Awesome](http://fortawesome.github.io/Font-Awesome/) library
* Add Theme Plugin dependencies:
	* [SiteOrigin Page Builder](https://wordpress.org/plugins/siteorigin-panels/) - required;
	* [Widgets Bundle](https://wordpress.org/plugins/so-widgets-bundle/) - optional;
	* [Image Widget](https://wordpress.org/plugins/image-widget/) - optional;
	* [Contact Form 7](https://wordpress.org/plugins/contact-form-7/) - optional;
	* [Menu Icons](https://wordpress.org/plugins/menu-icons/) - optional;
* Changed the include template path. Now the new path is `inc/templates`
* Created a `theme-functions.php` to centralize all functions instead `functions.php`
* `functions.php` is used for includes files only
* Separated scripts and styles includes in new file `inc/scripts.php`

The other documentation can be found at [Odin](https://github.com/wpbrasil/odin/blob/master/README.md).