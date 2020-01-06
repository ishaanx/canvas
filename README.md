# canvas-nest.js

A modified version of canvas-nest.js without mouse hover event.
This results in less CPU usage and removes the jitter effect. 

## Usage

+ Script tag
Insert the code below between <body> and </body>.

```html
<script src="js/canvas-nest.js"></script>
```

I strongly suggest to insert before the tag </body>, as the following:

```html
<html>
<head>
	...
</head>
<body>
	...
	...
	<script src="dist/canvas-nest.js"></script>
</body>
</html>
```

## Configuration

 - **`color`**: color of lines, default: `'0,0,0'`; RGB values: (R,G,B).(note: use ',' to separate.)
 - **`pointColor`**: color of points, default: `'0,0,0'`; RGB values: (R,G,B).(note: use ',' to separate.)
 - **`opacity`**: the opacity of line (0~1), default: `0.5`.
 - **`count`**: the number of lines, default: `99`.
 - **`zIndex`**: z-index property of the background, default: `-1`.

Example:

 - Script tag

```html
<script type="text/javascript" color="0,0,255" opacity='0.7' zIndex="-2" count="99" src="dist/canvas-nest.js"></script>
```

## Integration with Hexo

Put the canvas-nest.js in js folder
Include the script tag in layout.ejs before the </body>

```html
<script type="text/javascript" color="0,0,255" opacity='0.7' zIndex="-2" count="99" src="dist/canvas-nest.js"></script>
```


Original repo here - https://github.com/hustcc/canvas-nest.js


