brix
====

Summary
brix software component integration tools implemented with OpenGL


This project is for developing a super-fast cross platform graphical software development environment for generating and navigating software for the brix environment (www.inx-systems.net).

This project has been started by interns from Leeds University with the initial contribution of prototype software for implementing MDI with OpenGL windows and rendering key graphical features of the function-block-based brix development environment. This prototype software is contained in ./main/prototypes.

The trunk of the application software will be formed from the existing C++ code-base, where it will be ported from MFC to wxwidgets and OpenGL.

The application software is partitioned into the following categories:
./main/brix-tools/iab - the Component Integration-based Application builder
./main/brix-tools/common - shared code used in iAB and plugins.
./main/brix-tools/plugins/igb - the GUI builder plugin tool.
./main/brix-tools/plugins/idb - the database management plugin tool.





