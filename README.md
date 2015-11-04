gh-td
====

# Grasshopper <-> TouchDesigner Bridge for Polygon Mesh Geometry

(c) 2013-2015 

## Authors:

	- Gabriel Dunne [http://github.com/quilime/](@quilime)  
	- Ana Hurruzo  [http://github.com/ana00/](@ana00)

## Abstract

A collection of patches that send\receive polygon geometry from Grasshopper in realtime to TouchDesigner and visa/versa via OSC.

## Requirements

### Software
- [Rhino3D](http://rhino3d.com)
- [Grasshopper3D](http://www.grasshopper3d.com/)
- [TouchDesigner](https://www.derivative.ca/)

### Grasshopper Plugins
- [gHowl](http://www.grasshopper3d.com/group/ghowl)
- [GhPython](http://www.food4rhino.com/project/ghpython)
- [LunchBox](http://www.food4rhino.com/project/lunchbox) (Used for demo purposes)

## Examples

### Sending geometry from Grasshopper -> Touchdesigner

	1. open gh/sender.gh in Grasshopper
	2. open td/receiver.toe in TouchDesigner

### Sending geometry from Touchdesigner -> Grasshopper

	1. open td/receiver.toe in TouchDesigner
	2. open gh/sender.gh in Grasshopper

## Screenshots

### Grasshopper Sender
gh/sender.gh
![](https://github.com/quilime/gh-td/blob/master/screenshots/gh_sender.PNG)

### Grasshopper Receiver
gh/sender.gh
![](https://github.com/quilime/gh-td/blob/master/screenshots/gh_receiver.JPG)

### TouchDesigner Sender
td/receiver.toe
![](https://raw.githubusercontent.com/quilime/gh-td/master/screenshots/td_sender.JPG)

### TouchDesigner Receiver
td/receiver.toe
![](https://raw.githubusercontent.com/quilime/gh-td/master/screenshots/td_receive.PNG)

