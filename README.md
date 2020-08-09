# Grab Objects Advanced
_demo of grab-objects-advanced scene running in preview._

![demo](https://github.com/decentraland-scenes/grab-objects-advanced/blob/master/screenshots/grab-objects-advanced.gif)

## Description
Demonstrates how you can grab and move an object using the [cannon.js](https://github.com/schteppe/cannon.js) physics engine. This is the advanced version of this scene [here](https://github.com/decentraland-scenes/grab-objects). To view the scene, please visit [here](https://grab-objects-advanced.vercel.app/).

## Instructions
* Use your mouse to look around and <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> keys on your keyboard to move forward, left, backward and right respectively. 
* To jump, press the <kbd>Space</kbd> key.
* To grab the object, click and hold the <kbd>Left Mouse Button</kbd>.
* Press and hold the <kbd>E</kbd> key to pull the object in.

## Issues
There are a couple of issues that need looking at:
* Object reorientates itself when you first pick it up.
* Making large arcs/turns whilst holding the object can cause the object to go out of bounds.

## Try it out 
After you clone the project, run the following:

```
$ npm i -g decentraland
```

Followed by:

```
$ dcl start
```

## Acknowledgements
Code is adapted from https://github.com/schteppe/cannon.js/blob/master/examples/threejs_mousepick.html
