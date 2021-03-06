# NPTheme-Scripture
NotePlan app theme with parchment-and-leather look, and Bible cross-links

# Overview
This is a theme for the awesome Mac and iOS app "NotePlan" [link](https://apps.apple.com/us/app/noteplan-3/id1505432629)
The author, Eduard Metzger, recently added theming support, so this prompted me to try my hand 
at a simple theme that gave the feel of real paper, like many Bible apps do.  
On top of this, the "bold" font was repurposed to be "words of Christ" in bright red.

# Additional Features
Serendipitously, there is a linking feature in the theming mechanism, using simple Javascript/JSON regular expressions.   
So for any text matching a designated regexp, we can not only highlight the matched verse reference, but we can also send 
the matched text to a URL handler that can either open another app (X-url-callback) or append it to a base URL.  
This is a great option for Bible verse references in a note, sending the user straight to his/her favorite online Bible!

Bible Gateway would be a natural choice, but for the initial implementation of this theme, I couldn't figure out a way to reparse the fragments of a verse regexp into a snippet acceptable to the Bible Gateway syntax (URL-encoding of special characters, like space and ":").  So for now,
I simply send the verse citation to the OliveTree BibleReader app, which may Bible enthusiasts have on their devices already on their Mac or iOS devices.

You are free to copy and modify this theme to your liking, and my hope is that it provides a template for further improvements and options
(maybe you'll figure out the URL encode stuff before me!).  Please feel free to fork this repo and put in pull requests for changes you
think would benefit others

Thank you, and God bless!
-Rob Grace ("gracius" on Discord)
