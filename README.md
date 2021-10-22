## b4-sidebar

<div align="center"><img src="https://zeus2198.github.io/mockup.gif" width="600"/></div>


This is a responsive side-bar template for **Boostrap 4** with slide in/out interactive animations. It comes in two themes which are [dark]( https://github.com/zeus2198/b4-sidebar/blob/master/index.html) and [light]( https://github.com/zeus2198/b4-sidebar/blob/master/light.html). Dark theme is the default theme.

The side-bar hides in smaller screen and can be toggled with help of button in navbar. You do not need to make navbar separately, a part of side-bar it self is navbar which appears on smaller screen. Just follow the code pattern described below and you will be good to go. For proper examples, have a look at [index.html](https://github.com/zeus2198/b4-sidebar/blob/master/index.html) and [light.html](https://github.com/zeus2198/b4-sidebar/blob/master/light.html).

In the demo [font-awesome](http://fontawesome.io/) icons are being used, but you can use any.

# [Demo Dark]( https://zeus2198.github.io/b4-sidebar/) | [Demo Light]( https://zeus2198.github.io/b4-sidebar/light.html)
Zoom in to view how it would look in mobile and try toggling the sidebar!

# General Structure

The code structure for sidebar is as follows :
```html
<div class="side-bar">
	<!-- add class "side-bar-light" here for light version -->
	<nav class="navbar navbar-inverse">
		
		<!-- toogle button -->
		<button class="navbar-toggler hidden-lg-up" type="button" id="toggler" aria-controls="list-container" aria-label="Toggle side-bar">
			<span class="navbar-toggler-icon"></span>
		</button>
		
		<!-- brand name goes below -->
		<a class="navbar-brand" href="#">Brand</a>
		<div class="list-container">
			<ul>
				<!-- list of side bar elements goes here, example : -->
				<li><a href="#" class="active"><span class="navIcon"><i class="fa fa-sticky-note"></i></span>&nbsp;&nbsp;Active Link</a></li>
			</ul>
		</div>
	</nav>
</div>
<div class="bodyContent">
	<!-- Body content here -->
</div>
 ```

As mentioned in comments to switch to lighter theme of side-bar just add the class `side-bar-light` where class `side-bar` is being used. (Note that you need to add this class for light version **not replace it)**

# License 
This project is licensed under the terms of the [MIT license](https://en.wikipedia.org/wiki/MIT_License)



