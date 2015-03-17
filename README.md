# ofxKinectTest

This is a test/sandbox Xcode 6.2 project that users openFrameworks, libfreenect2, Box2D and code from @ofTheo,
who wrapped the Protocnet sample project from libfreenect2 to OFX; also from @vanderlin, who wrapped the amazing
Box2D library. It works with Kinect V2 and OSX running Yosemite (did not test any other machines yet).

More info:

- https://github.com/OpenKinect/libfreenect2
- https://github.com/ofTheo/ofxKinectV2
- https://github.com/vanderlin/ofxBox2d

In order to make this work, start with **libfreenect2** and all its dependencies, including Homebrew.

I used OFX 0.8.4 and the Project Generator to create this project, I only included some headers' search
and some basic code to make it compile and run.

**ofxBox2d** is an addon for OFX, and it must be placed in the **addons** directory before running the Project
Generator.
