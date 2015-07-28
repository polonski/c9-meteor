# c9-meteor
my attepts at polymer inside meteor on c9.io. The main thing I'm trying to fire up inside meteor is the ```paper-drawer-panel``` . 

## install / repro sequence
- ``` > meteor create a ```
- ``` > cd a ```
- ``` > meteor add loneleeandroo:polymerize ```
- ``` > meteor ```

 * let meteor start and initialise polymerize
 * stop meteor 
 
- ``` > bower install --save PolymerElements/iron-elements#^1.0.0 ```
- ``` > meteor ``` 
 
 * let meteor start and add iron-elements
 * stop meteor

- ``` > bower install --save PolymerElements/paper-elements#^1.0.0 ```
- ``` > meteor ```

 * let meteor start and add paper-elements 

## cleanup
I removed most of the dependencies from bower.json, leaving only what I need. Still can't get ```paper-drawer-panel``` to work, as the 'CSS can't be read' error shows only for this element. Others are working OK.

## working?
~~This works in the browser preview pane inside the c9.io IDE, but~~ it does not work using any 'real' browser.
 

## demo
a running version of this demo is here https://meteor-polonski.c9.io/

