jquery.rainbow
==============

Animated rainbow text jQuery plugin

Usage
-----
	$(node).rainbow();

To stop the effect, simply do:

	$(node).rainbow(false);

You can set the following options:

	$(node).rainbow({
		start:     0,               // set to "random" to randomize the start, otherwise leave as 0
		width:     Math.PI / 16,    // width of color bands
		speed:     Math.PI * 64,    // speed at which the colors change
		timeout:   50,              // milliseconds between each update, set low for smoothness
		redPos:    2 * Math.PI / 3, // position of the start of the red band
		greenPos:  0,               // position of the start of the green band
		bluePos:   4 * Math.PI / 3, // position of the start of the blue band
		className: "rainbow",       // class name for node rainbowifying
		spanName:  "jQueryRainbow", // class names for all the helper <span>s
	});
