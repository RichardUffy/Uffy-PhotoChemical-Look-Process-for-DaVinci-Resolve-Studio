# UffyLook Github Readme v1 - 09/04/25
### Intro
UffyLook is a system that's designed to give a film-like look. It's a built into Resolve & is adjustable as a look development tool, built from different component DCTLs. 

**DaVinci Resolve Studio is Required**
### Installation
**First Component** to install is the LUTs & DCTLs. Please place these in the Resolve LUT folder on your system, this required for everything to work

**Second Component** in a Power Grade so it can be used in the Node Graph. 

**Please Familiarise** With the concepts of LUTs, DCTLs & Power Grades in DaVinci Resolve
### Usage in Resolve
The entire process is based on DaVinci Wide Gamut & DaVinci Intermedtial as a working Colour Space & Gamma. Primary to be used in a Node Based Colour Managed workflow. Any footage that's not in these working a Colour Space Transform (CST) will need to be used, eg Arri Log C3/Arri Wide Gamut3 or Canon Clog2/Cine Gamut will to be transform to DaVinci Intermediate/DaVinci Wide Gamut used a CST node. 

The Main UffyLook Power Grades are designed to be either Clip Group or Timeline level. 

A CST to DaVinci Intermediate/DaVinci Wide Gamut from the camera's original space/gamut will need to be place before the UffyLook Node graph.   
#### Modifying Default Parameters
This part of the guide will be coming soon. 
#### Thanks to & Forked from
Thatcher Freeman: https://github.com/thatcherfreeman
Hotgluebajo: https://github.com/hotgluebanjo/halation-dctl
Npeason: https://github.com/npeason/Tetra-DCTLOFX
AGX: https://github.com/sobotka/AgX-Resolve
Cullen Kelly: https://cullenkellycolor.com/
