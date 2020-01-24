**WARNING: This repo is archived for the obvious reasons and you really should not use it. It only here because of nostalgia**

# jQuery panr

Zoom and panning effect

[demo/](http://robertbue.no/plugins/jquery.panr/demo.html)

## Usage

1. Include jQuery and GSAP:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
	<script src="http://cdnjs.cloudflare.com/ajax/libs/gsap/1.11.1/TweenMax.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="jquery.panr.js"></script>
	```

3. Call the plugin:

	```javascript
	$("#element").panr({
		sensitivity: 30,
		scale: false,
		scaleOnHover: true,
		scaleTo: 1.1,
		scaleDuration: .25,
		panY: true,
		panX: true,
		panDuration: 1.25,
		resetPanOnMouseLeave: false,
		onEnter: function(){},
		onLeave: function(){}
	});
	```

## License

This plugin is available under the [MIT license](http://opensource.org/licenses/mit-license.php).

## Author

Made by [Robert Bue](http://robertbue.no)
