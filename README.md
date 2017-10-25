# scroll-navigation
This plugin activates the nav links based on the scroll position of the content.
Default classes are : 

'nav' --  the navigation container

'scrollNavData' --- the scroll data container

'scrollNav-links' --- nav link class

'scrollNav-active' --- active class for highlighting the active contnet link

'scrollNav-content' -- the class marking the content block


# Dependency
requires jQuery library


# Usage:

$(document).ready(function(){
    var s = new scrollNav();
    s.init();
});

You can pass all the arguments -- (offset,navCont,dataCont,linkClass,activeClass,contentClass) to scrollNav


