brix
====

Summary
brix software component integration tools implemented with OpenGL


This project is for developing a super-fast cross-platform graphical software development environment for generating and navigating software for the brix environment (www.inx-systems.net). The aim of the project is to provide an unencombered  development environment that can be edited at least as quickly as a text-based development. 

This project has been started by interns from Leeds University with the initial contribution of prototype software for implementing MDI with OpenGL windows and rendering key graphical features of the function-block-based brix development environment. This prototype software is contained in ./prototypes.

The trunk of the application software will be formed from the existing C++ code-base, where it will be ported from MFC to wxwidgets and OpenGL.

The application software is partitioned into the following categories:
./brix-tools/iab - the Component Integration-based Application builder
./brix-tools/common - shared code used in iAB and plugins.
./brix-tools/plugins/igb - the GUI builder plugin tool.
./brix-tools/plugins/idb - the database management plugin tool.





