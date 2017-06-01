![Logo](https://2oieu24ejvlgafc161o49t49-wpengine.netdna-ssl.com/wp-content/uploads/2014/09/scroll_to-637x358.jpg)

# smoothScroll
A better version of zenScroll which doesn't break your other JS code. Basically event bubbling is kept.  That's it.

# example use
import smoothScroll from './smoothScroll' 
//Smooth scroll back to top for sidebar
var defaultDuration = 600
var edgeOffset = 10
var sideBarDiv = document.getElementById("sideDiv")
var mainDiv = document.getElementsByClassName("nav") 
var scrollSlow = smoothScroll.createScroller(sideBarDiv, defaultDuration, edgeOffset)
var scrollFast = smoothScroll.createScroller(sideBarDiv, defaultDuration, edgeOffset)


No license, based on zenscroll, which also had no discernible license.  All original credit etc goes to them, anyone.  Have fun.