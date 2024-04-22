## Name

timelapse.lua - timelapse - process a timelapse image sequence

## Description

timelapse reads a sequence of images looking for keyframes that
set parameters for an included set of images.  Once the keyframes 
are found, they are processed to get the setting information then
each image in the set is processed and the settings applied.

Image processing modules are contained in lib/modules.  This 
architecture allows adding new processing modules at any time
without any code changes to the main program. 

## Usage

* Install using script_manager.
* Start the script using script_manager.
* Start the module.  Enable the desired modules.
* Create and tag keyframses in the script.
* Run the processing.

## Additional Software Required

None

## Limitations

None

## Author

Bill Ferguson - wpferguson@gmail.com

## Change Log
