DevSuiteSDK
===========
The DevSuiteSDK is a Software Development Kit for Aptina's USB Demo Hardware(
Demo2X, Demo3).
For the full DevSuite Installation for Windows go to:
 http://www.aptina.com/support/Devsuite.jsp

This distribution includes some of the basic libraries/APIs which are now
available for Mac OS X and Linux

This distribution now includes the DevWareX application.
DevWareX is a Qt based version of DevWare that runs on Mac, Linux and Windows.
This is an early release of the application, so it doesn't include all of the
features.
Please see the release notes for what is currently supported.

There are two sample applications currently available.
[SimpleCapture](samples/SimpleCapture) is a command line application that grabs
an image from the demo camera.
It is based on the [ApBase](include/apbase.h) library.
[SimpleQt](samples/SimpleQT) is a GUI based Qt application that displays the
images from the demo camera.
This is also based on the [ApBase](includeapbase.h) library.

The non-NDA data files are located in apps_data (initialization files) and
sensor_data (register reference file).
For other parts please copy your data files into these directories.

For support or feedback please email imaging_demo_bugs@aptina.com
