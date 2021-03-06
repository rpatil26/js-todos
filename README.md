# js-todos
Simple TODO application built using vanilla JS, HTML, CSS and React for the Views.

# About
* This is sample TODO MVC app built using vanilla JS, HTML and CSS code. 
* It now uses [React] (https://facebook.github.io/react/index.html) for the Views.
* It can be plugged with remote todo server here (https://github.com/rpatil26/node-todoserver)
* Or it works localStorage (in js memory storge if localStorage is not available)

# Live Demo
**https://rawgit.com/rpatil26/js-todos/master/index.html** (uses localStorage)

# Screenshot
![alt screenshot](https://raw.githubusercontent.com/rpatil26/js-todos/master/screenshot.png)

# Functional
* Task listing
* Task check/uncheck - marks complete/pending 
* Only Completed task can be deleted 
* Keyboard navigation and accessibility
* Task filter by state - All, Pending (incomplete) or Completed ones
* Provides visual feedback with light animation 
* Responsive and renders well across devices

# Technical
* Implemented tiny js lib for common things
 * Observer pattern for listening, dispatching events - EventTarget
 * Custom callback that binds with the object scope and can override arguments
 * Simple iterator $each 
 * AjaxLoader to wrap XMLHTTPRequest 
 * Inheritance - Extend
 * Basic templating - $template string based templates - ({token} expansion)
 * Interface enforcement concept - Defining and Implementing - Impls
* MVC design - Need to clean and refine further
* Uses CSS3, pseudo classes etc. Uses no images or tables. 
* Custom (non native) checkbox using CSS, HTML entity and anchor

