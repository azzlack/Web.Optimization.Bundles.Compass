Web.Optimization.Bundles.Compass
================================

Compass SASS/SCSS processing for System.Web.Optimization bundles.

### Usage
You need to have [Ruby](http://rubyinstaller.org/downloads/) and [Compass](http://compass-style.org/install/) installed.    
Also, the Ruby `bin` path must be placed in your `Path` environment variable.  
(This should happen automatically)

### Limitations
**[When bundling/optimization is disabled](http://www.asp.net/mvc/tutorials/mvc-4/bundling-and-minification)**  
The resulting CSS files will not be updated before you compile your site or touch the web.config.