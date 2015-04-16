# What is slimScroll?

slimScroll is a small jQuery plugin that transforms any div into a scrollable area with a nice scrollbar - similar to the one Facebook and Google started using in their products recently. slimScroll doesn't occupy any visual space as it only appears on a user initiated mouse-over. User can drag the scrollbar or use mouse-wheel to change the scroll value.

Demo and more: http://rocha.la/jQuery-slimScroll

Copyright (c) 2011 Piotr Rochala (http://rocha.la)
Dual licensed under the MIT (http://www.opensource.org/licenses/mit-license.php) and GPL (http://www.opensource.org/licenses/gpl-license.php) licenses.

added option over librarry of rochal 
jQuery('#scroll').slimScroll({
        height: jQuery(window).height()+'px', //if you want whole page containing div to get scroll it's a trick only
        mouseOver:true // if element you want to scroll will already hovered then make it true else no need to mention it.
    });
