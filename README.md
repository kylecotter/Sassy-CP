Sassy CP
==============================================================

Sassy CP is a twist on the common override.css. Sassy CP is built on the SASS css preprocessor. This allows for easy skinning of the CP to meet your needs.

Extending on the default CP theme, Sassy CP cleans up some rough edges, improves the user experience, and makes a great interface for your clients to use.

Installation
-----------

For an "out of the box" installation, where you won't be recompiling the SASS, follow these steps:

1. Navigate to your "themes/cp_themes" folder.
2. Add the "Sassy_CP" folder in to the "cp_themes" folder.
3. Delete the "sass" folder inside the "Sassy_CP" folder.
4. Open "system/expressionengine/config/config.php" and add " $config['cp_theme'] = 'Sassy_CP'; "
5. Your control panel should now have the override applied.

Getting Sassy
--------------

Sassy CP is built upon the SASS preprocessor, and Compass framework.

You must be running SASS and Compass on your system to make use of the configuration of Sassy CP.

1. Navigate to your "themes/cp_themes" folder.
2. Add the "Sassy_CP" folder in to the "cp_themes" folder.
3. Open "system/expressionengine/config/config.php" and add " $config['cp_theme'] = 'Sassy_CP'; "
4. Your control panel should now have the override applied.
5. Open Terminal, and navigate to the directory your ExpressionEngine site lives in.
6. Navigate to "themes/cp_themes/Sassy_CP/sass" in Terminal and run "compass watch".
7. Inside the "sass" folder, you will see all the files associated with Sassy CP. Open "_config.scss". Note this is referring to the SCSS file and not the Ruby config file.
8. Inside ""_config.scss" you'll find a number of variables you can set and alter. In most cases, the $primaryColor and boolean variables will be the only ones you need to alter.
9. Once you've made your change, save the config file and let Terminal recompile the CSS.
10. Refresh the ExpressionEngine Control Panel, and your changes should be visible.
11. If you are no longer going to alter the ExpressionEngine CP via Sass, delete the "sass" folder.

Pre v1.1.0 Updating
-----------

If you are using a version prior to v.1.1.0, where Sassy CP is no its own theme, follow these steps to update.

* Navigate to "themes/cp_themes/default/css".
* Delete "override.css".
* Follow "Installation Instructions" above.

Screenshots
-----------

* Easy skinning <img src="http://cl.ly/IbPq/Screen%20Shot%202012-08-07%20at%2011.34.01%20PM.png">
* Control Panel Home Page <img src="http://cl.ly/JRdZ/Screen%20Shot%202012-09-12%20at%209.16.51%20PM.png"> 
* Template Manager <img src="http://cl.ly/JQD0/Screen%20Shot%202012-09-12%20at%209.18.33%20PM.png">
* Edit Channel Entries Page <img src="http://cl.ly/JQT2/Screen%20Shot%202012-09-12%20at%209.19.08%20PM.png">

Changelog
-------
* v2.0.0 - Rewritten styles, custom configuration via SASS, more compact styles. Full compatibility with popular third-party add-ons.
* v1.2.1 - Fixed an instance of pink that would display on Wygwam configuration page.
* v1.2.0 - Added a login.css for the main admin login screen. Enhancements on the category page, various modals, and tweaks for ExpressionEngine 2.4 compatibility.
* v1.1.0 - Converted from override to a CP theme. Replaced pink images, and tweaked other styles.
* v1.0.3 - Bug fixes.
*  v1.0.2 - Bug fixes.
*  v1.0.1 - Bug fixes.
*  v1.0.0 - Initial Release

Credits
-------

Created by Kyle Cotter. Licensed under <a href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution 3.0</a>.

Check out <a href="http://eehash.com">EE Hash</a> for the latest ExpressionEngine news and <a href="http://cotterinteractive.com">Cotter Interactive</a>.