# c9-meteor
my attepts at polymer inside meteor on c9.io. The main thing I'm trying to fire up inside meteor is the ```paper-drawer-panel``` . 

## bugs related to this
- https://github.com/loneleeandroo/meteor-polymerize/issues/8
- https://github.com/Polymer/polymer/issues/1712

## install / repro sequence

After initally trying to wrangle polymer elements using polymerize, I got rid of polymerize altogether and am now importing polymer elements directly in the a.html file

However removing Polymerize has not made a difference and the issue is still happening. Polymerize is great for installing polymer, keeping the dependencies in ```bower.json```, which I like so I'll go back to that once this is sorted.

## cleanup
I removed most of the dependencies from bower.json, leaving only what I need. Still can't get ```paper-drawer-panel``` to work, as the 'CSS can't be read' error shows only for this element. Others are working OK.


## demo
a running version of this demo is here https://meteor-polonski.c9.io/

