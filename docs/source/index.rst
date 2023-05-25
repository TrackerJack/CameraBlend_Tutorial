===================================
CameraBlend
===================================


What is CameraBlend?
---------------------------------
.. Insert animated gif here

The fast and easy way to animate a complex camera move is to morph between 2 different cameras. With CameraBlend simply select the two cameras and optionally an object to track to, press the hotkey and a new BlendCam is created that can be animated between the cameras.

---------------------------------
Why?
---------------------------------
Any camera transition or complex animation that might be simplified by creating 2 different cameras and blending.
Non destructive workflows. 
Directorial changes.

---------------------------------
How?
---------------------------------
Select the first camera then the second then press the trigger key (the default is shift alt/option B) and your new BlendCam is created. The last camera selected will always be the start (0% Blend) position.

---------------------------------
How to track to a target
---------------------------------
Select the object you want the BlendCam to track to before selecting the cameras and pressing the trigger key (the default is shift alt/option B) and your new BlendCam is created with a tracking constraint to the selected object.


---------------------------------
How to Animate between Cameras
---------------------------------
Select the newly created Camera 'CameraBlnd'
Adjustments and keyframes can be applied to the 'Blend' Custom Property in the Camera properties panel
Camera properties panel > Custom Properties > Blend

---------------------------------
Features
---------------------------------

* Fast and Easy to use
* Changes to the source cameras are instantly updated to the Blend Camera.
* Combine 3D tracked camera data with smooth animated cameras.
* Transition from  Camera to another



.. toctree::
   :maxdepth: 2
   :caption: Contents:

   index
   installation
   quick_start
   
.. note::
   This project is under active development.
   

