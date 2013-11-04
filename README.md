# jQuery panr

Zoom and panning effect

## Usage

1. Include jQuery and GSAP:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
	<script src="//cdnjs.cloudflare.com/ajax/libs/gsap/1.11.1/TweenMax.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="jquery.panr.js"></script>
	```

3. Call the plugin:

	```javascript
	$("#element").panr({
		sensitivity: 30,
		scale: true,
		scaleOnHover: false,
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


#### [demo/](demo.html)

Contains a simple HTML file to demonstrate your plugin.