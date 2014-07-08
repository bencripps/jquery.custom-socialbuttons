jQuery-customSocial Buttons
===========================

This is a tiny jQuery library which helps create some social buttons in a snap. All elements are customizable through plugin attributes, and the library requires no exterior style sheets.

This has been tested on Firefox, Chrome, and IE8+ on Linux, and Firefox and Chrome on Windows. Will work with all modern browsers.

See [jQuery-customSocial](http://benjamincripps.com/customSocial/demo.html) for more information.

Features:
---------

Completely customizable:

	Every aspect of the element, including the container, icons, and styling can be modified using the plugin. Event handling for all types of user interaction. No external CSS needs to be used, but can be added easily using the .customIcon class.

Super Simple:

	What you see is what you get, just a simple social tab without all the fuss. Set up in seconds, but no compromise on customization.

No Weight: 

	The plugin file size is under 5k gzipped.

Easy to Use: 

	Full documentation on all available attributes and methods.

Attributes/Methods:
-------------------

Available Networks/Icons: facebook, twitter, email, github, google plus, flickr, linkedin, instagram, pinterest, tumblr, vine.

Icon Attributes:
	
`mainColor` (string) used to set the color of the icons.

`iconMargin` (string) used to set the spacing of the icons.

`iconSize` (string) text-size for the icons.

Container Attributes:

`width` (string) width of the container. the container will default to 100% if no width is specified. 

`backgroundColor` (string) background color for the container.

`border` (string) border width, detail, and color. the default is none. 

`roundedBorder`: (string) border-radius for the container. the default is none.

Events:

`customHover`: (boolean) the plugin has a builtin hover method which applies opacity on mouseenter. the animation is done using the jQuery animate event.

`onContainerClick`: [function] custom callback can be defined by user. a single argument is available, the jQuery object which has been clicked.

`onContainerMouseenter`: [function] custom callback can be defined by user. a single argument is available, the jQuery object which has been entered.

`onIconClick`: [function] custom callback can be defined by user. a single argument is available, the jQuery object which has been clicked.

`onIconMouseenter`: [function] custom callback can be defined by user. a single argument is available, the jQuery object which has been entered.

Questions:
----------
If you have any questions, please contact me at ben@benjamincripps.com. 
