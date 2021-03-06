# ofxmagnetic
Automatically exported from code.google.com/p/ofxmagnetic

Magnetic is an openFrameworks add-on developed at Fashionbuddha to meet our needs in creating high performance computer vision applications made to attract people. Its feature set exists to address issues that come up in real world public installation scenarios.

Magnetic's integration directly into our openFrameworks applications significantly reduces development time and eases calibration in any environment. When adjusting settings, we see what the camera sees, overlayed on the application. Calibration points may be adjusted both by touching on-screen points and using arrow keys to fine tune warping. Settings and calibration points are big and bright -- essential when dialing in large or oddly shaped surfaces. All adjustments are made through an intuitive keyboard interface, eliminating the need for a mouse.

ofxMagentic applications are created by extending the ofxMagneticApp class instead of ofBaseApp, relieving even novice ofx developers of implementation pains. An ofxMagnetic application works just like an ofBaseApp, but comes with a "getBlobs()" function that returns a list of blobs, their outlines, and peaks and valleys. This means that we can use Magnetic to make everything from pinpoint accurate multi-touch applications to augmented reality pieces that work with nothing more than a camera pointed at an audience.
