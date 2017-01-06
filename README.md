# bootstrap-three-reduced
Various selectors removed from Twitter Bootstrap stylesheet to reduce page load time.
## Overview
*Removed these selectors from Bootstrap 3 to reduce page load time:
-glyphicons;
-text-[selectors] (not text-aligns like text-justify, text-nowrap);
-blockquote-[special] (all but standard blockquote selectors);
-kbd;
-has-[] (all has-selectors, you can use .alert in place of);
-breadcrumb;
-pagination;
-pager;
-jumbotron;
-tooltip;
-popover;
* Included images to relplace font-awesome icons
* 4 icons created only, .png files with attributes

## Motivation
Main motive is to create a faster loading CSS file. The overhead on a slower computer was bogging down my editor. I use Bluefish on a 64 Linux Mint Intel i3 with 4GB of RAM. This should be good enough but several editors do not like loading the page with large files.

## Installation
* none, really. Just use stylesheet as is or partial out even more.
* Test file ("tests.html") to check usage in production.

## Contributors
Open for contributions. 
Thanks Twitter Bootstrap 

## License
Licensed under MIT License (MIT). 
http://opensource.org/licenses/MIT

## ToDo
- remove btn-groups
- maybe have one .btn style and allow for user insert background
- remove progress bars
- remove media-direction

