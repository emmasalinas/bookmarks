# Bookmarks
How to make magic buttons (in chrome):

1. open chrome://bookmarks/ and "Add new bookmark"
2. instead of a URL, put javascript (examples below)
3. move the ones you create to the top of the list
4. make your bookmarks bar visible


# Examples
I'll keep a list of ones I like and use frequently. Please add to this list.




### A button to skip youtube ads
_javascript: (function(){document.querySelector('video').currentTime = document.querySelector('video').duration})()_

### A button to 2X videos, everywhere
_javascript: (function(){document.querySelector("video").playbackRate = 2})()_
### make videos 25% faster
_javascript: (function(){ document.querySelector("video").playbackRate = 1.25*document.querySelector("video").playbackRate})()_
### make videos 25% slower
_javascript: (function(){ document.querySelector("video").playbackRate = 0.75*document.querySelector("video").playbackRate  })()_
