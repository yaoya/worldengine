Version 0.19-UNRELEASED

* Added export support using libgdal
* Force rivers and grayscale_heightmap to PNG to avoid ambiguity of providing a 
filename which can introduce input error.

Version 0.18

* Merged Lands and WorldSynth into one WorldEngine
* River and its erosion are now taken into account
* Total restructuring of code including many bug fixes.
* Windows/OSX/Linux binary builds

Version 0.5.4

* Fix bug in sea representation for elevation map
* Fix plates operation
* [Technical] Increase test coverage


Version 0.5.3

* Saving generation parameters in world file (Russell Brinkmann)
* Revising command line options (Russell Brinkmann)
* Adding tracing statements about performance (Russell Brinkmann)


Version 0.5.2

* Basic GUI implemented, supporting all views and simulations


Version 0.5.1

* Packaging lands as a script
* Supporting protocol buffer serialization
* QT based Gui


Version 0.5.0

* Supporting python 3
* Initial GUI (only plates simulation)


Version 0.4.3

* Adopting plate-tectonics (my fork of platec) which permits rectangular plate calculations


Version 0.4.2

* Generation of rivers map
* Stefan Feltmann ported Lands to Pillow (removing PIL)


Version 0.4.1

* Generation of grayscale heightmap


Version 0.4.0

* Evan Sampson added Holdridge life zones model










