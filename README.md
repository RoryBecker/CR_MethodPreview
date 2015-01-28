# 'Method Preview' for CodeRush #

Provides an action '**ToggleMethodPreview**' actionable from any method call whose source is available and provides that source as a preview window.

### Configuration ###
 * Assign the '**ToggleMethodPreview**' to a key. (see [Binding a Key](http://rorybecker.blogspot.com/2009/08/how-to-bind-key-in-coderush.html))

### Usage ###

 * Place caret on any Method Call for which the source is available within the solution.
 * Activate the '**ToggleMethodPreview**' action using whichever key you bound to it.
 * Deactivate when done, using the same key.

### Notes ###

* This plugin currently shows the entire method.
* The plan is to limit this to the first n (defaulting to say 30) lines. However the DXCore currently needs the entire method in order to format things correctly.
