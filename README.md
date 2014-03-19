# SASS

A collection of useful mixins

- __functions__
	- __get-column-margin()__  
	A mixin for calculating the column margin for columns.
- __media-queries__
	- __breakpoint()__  
	Useful for making breakpoints more abstract.
	- __webkit-only()__  
	Targets webkit only.
	- __retina()__  
	Targets retina devices only.
- __typography__
	- __font()__  
	Handles IE8 font-face bug.
	- __word-break()__  
	Breaks long words when then extend past the container.
- __layout__
	- __pseudo()__  
	Typical attributes for pseudo elements.
	- __image-replacement()__  
	Use to hide text when links are only icons.
	- __horizontal-center()__  
	For horizontally centering a psuedo elements.
	- __vertical-center()__  
	For vertically centering a psuedo elements.
	- __vertical-center-relative()__  
	Use to vertically center dynamic amounts of text in a parent container.
	- __clearfix()__  
	Generic clearfix to make a parent stretch to contain floated children.
	- __full-size-absolute()__  
	Useful when you need an absolute positioned child to be maintain the dimensions of it's parent.
	- __sprite()__  
	Mixin for creating retina supported background sprites.
- __columns__
	- __column-border-base()__  
	This base for both column-border() and column-wrapper-border() used to add the pseudo element.
	- __column-wrapper()__  
	Use this wrapper when including columns.
	- __column-wrapper-border()__  
	This allows you to add a border to the top or bottom of a column since a the padding would make it too wide for the grid.
	- __column()__  
	Use if multiple columns are in a row.
	- __column-row-break()__  
	If you need to start a new row of columns add this mixin.
	- __column-base()__  
	Base class for column-width and column-offset.
	- __column-width()__  
	Simply adds the width and padding need for the column width.
	- __column-offset()__  
	Only adds margin and padding to offset an element in increments of the grid.
	- __column-border()__  
	This allows you to add a border to the top or bottom of a column since a the padding would make it too wide for the grid.
	- __column-include-gutter()__  
	Used inside a column to create an element that spans to the outside of the gutter.
	- __column-auto-height()__  
	Makes column backgrounds all appear to be the same height. Paren should be overflow hidden.
- __forms__
	- __input()__  
	Clears default styles and adds box-sizing.
	- __placeholder()__  
	Allows you to style placeholder color across various browsers.
	- __submit()__  
	Clears default styles to make submits render and function more like links.
- __css3__
	- __vendor-prefix()__  
	Adds webkit and moz prefixes and o and ms optionally.
	- __background-size()__  
	Mixin for css3 fallbacks.
	- __border-radius()__  
	Mixin for css3 fallbacks.
	- __box-shadow()__  
	Mixin for css3 fallbacks.
	- __box-sizing()__  
	Mixin for css3 fallbacks.
- __patterns__
	- __class-set()__  
	This is useful when a set of classes is consitently tied to a visual style.
	- __sprite-set()__  
	An easy way to absract you srpite sets so your background offset isn't littered all over your css.
	- __breakpoint-set()__  
	A way to set up different images for different breakpoints.