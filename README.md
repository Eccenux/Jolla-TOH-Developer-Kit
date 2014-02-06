Jolla-TOH-Developer-Kit
=======================

Jolla TOH (The Other Half) Developer Kit. A fork of Jolla specs and models. 

For an original kit go to: [jolla.com/the-other-half-developer-kit](http://jolla.com/the-other-half-developer-kit).

Modifications
------------- 

* `jolla-toh.original.blend` - blender import of original STL file.
* `jolla-toh.blend` - fixed (removed) non mainfold edges (STL export available).

See "3D" folder for the mentioned files

Blender - the 3D editor
-----------------------

### Using Blender for 3D print checks ###

* STL support is built in (File -> Import -> STL).
* 3D Prinitng tools can be installed by goining into: File -> User preferences -> Addons (search for "print").
* Moving around cheat sheet:
	* Scene rotation: MMB (hold and drag)
	* Zoom: Wheel or CTRL+MMB
	* Strafe (left/right): CTRL+Wheel
	* Move (up/down/left/right): SHIFT+MMB
* Import and check:
	1. New scene.
	2. Remove default cube: Edit mode (bottom left menu) -> RMB -> Delete -> Verticies.
	3. File -> Import -> STL
	4. On the left choose "Solid" check in 3D Print section. Results should appear below.
	5. To view results go into edit mode and click on the button.
* Searching for commands by pressing Space bar.   
* Useful commands:
	* View Selected (CTRL+NumPad.) - centers on selected edges/verticies.
	* Snap Cursor to Selected - makes zooming easier.
	* Center view to mouse - changes rotation center.

### Links ###

* [Nice Blender tutorial](http://www.katsbits.com/tutorials/blender/learning-keyboard-mouse-navigation.php).
* [3D Printing Toolbox](http://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Modeling/PrintToolbox).