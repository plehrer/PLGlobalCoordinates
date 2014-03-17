PL3DGlobalCoordinates
=====================

Global Coordinate Object Tracking Program
=========================================

This program uses OpenCV version 2.4.8 to track a colored object and find the 
3D global coordinates. Red, Blue or Yellow can be set from a switch.  Before
running this program you must calibrate a stereo camera to get the appropriate matrices.

For a good description on how to do the calibration, along with the code to calibrate
the stereo camera see the Martin Peris blog on [OpenCV Stereo Calibration](http://blog.martinperis.com/2011/01/opencv-stereo-camera-calibration.html)

- It is compiled in Xcode and assumes OpenCV was installed using MacPorts.
- For a good tutorial on setting up OpenCV on a Mac try [this link](https://gist.github.com/balazspete/6982565)