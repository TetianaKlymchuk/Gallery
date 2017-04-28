# Gallery
## This is simple and effective HTML photo gallery using CSS and JavaScript
I use FancyBox 3, jQuery lightbox script for displaying images, videos etc, for create all features appear on the screen. For this reason it is needed to add latest jQuery and fancyBox files. 

Once you've been trying this plugin, you'll forget about all other alternative plugins.
Very cool thing that will allow you to open:
* Pictures and Picture Galleries;
* Ajax windows;
* YouTube videos and videos from other services;
* Iframe windows;
* Modal windows with their contents
on your website.

Here you can find an screenshots:
![Screenshot](https://cloud.githubusercontent.com/assets/28005338/25487847/179d2ee0-2b6e-11e7-8378-daf7ab6aa54e.png)

![Screenshot](https://cloud.githubusercontent.com/assets/28005338/25487869/22d8cdaa-2b6e-11e7-9db6-bf71cd69aad3.png)

Tips:

* _Make sure you add the jQuery library first;_
* _If you already have jQuery on your page, you shouldn't include it second time;_
* _Do not include both fancybox.js and fancybox.min.js files;_

To bind fancyBox events on any element, select with a jQuery selector and call the fancybox method:
```
<script type="text/javascript">
	$("[data-fancybox]").fancybox({
		// Options will go here
	});
</script>
```
Some of possible plugins:
```
<script>
$("[data-fancybox]").fancybox({
// animation speed
speed : 330,
// Paddings (this command will be ingnored if width of the window less than 800px)
margin : [44, 0],
// Horizontal padding between slides
gutter : 30,
// Control panel
infobar : true,
buttons : true,
// Buttons on the control panel
slideShow  : true,
fullScreen : true,
thumbs     : true,
closeBtn   : true,
// Image
image : {
// wait for upload before the demontration
preload : "auto",
// Protection from the right-click download 
protect : false
}
});
</script>
```
