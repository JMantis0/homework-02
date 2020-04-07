# Responsive Web Portfolio with Bootstrap CSS Framework

The goal of this project is to make a web application that will serve as a portfolio and point of contact which renders well on a variety of devices, windows, and viewport sizes utilizing the Bootstrap CSS Framework

------------------------------------------

Accomplishing this will create a web application that can be universally viewed by users of all different types of browsers, devices, and windows at any size the user wishes.

## Challenges faced in the project

When beginning this assignment my experience with CSS frameworks was very limited. Getting columns to layer inside rows and have them appear in the browser as desired was a slow process at first; a process that involved a lot of experimentation, trial and error, and reading of Bootstrap documentation.  In addition to that is the additional challenge of geting the layouts to adjust in a functional and aesthetic manner as viewport sizes change and across other mobile devices.

I found that conceptualizing the layout on paper with a sketch of how I wanted rows and columns to rest on the page before diving into the code was helpful.

I soon discovered that Bootstrap's framework documentation provides an immense number of prebuilt classes and utilities that give the coder many tools and options to create a tremendous variety of layouts that are RESPONSIVE across platforms.  Praise be to the creators of open-source code!

I found myself getting stuck on small details quite a bit.  Sometimes something would appear just a little bit off and it would take me some time to figure out why, and what to do about it.

Once I had a decent looking structure for the first page, constructing the other pages with my own code and slowly growing understanding of the Grid System was considerably easier.

I also found that it was possible to use a single css document to apply to all 3 pages, but I believe it would be more efficient to seperate the css into 3 documents given more time.

### What I learned

Methods to manipulate the rendering and appearance of html structures across platforms and dynamically changing viewport.  Examples include media quiries and Bootstrap grid utilities.

How to research Bootstrap documentation and use open-source code to add useful prebuilt html structures to my website. Examples include: nav bars, cards, forms, and buttons.

How to utilize prebuilt framework classes such as columns and rows to control how elements render.

The value of spending time sketching out a design on paper before diving into coding.

That 

```html, body {
	margin: 0;
	height: 100%;
}
```
Can resolve issues where background image does not fill the whole screen on some browsers.