gh-td
====

# Grasshopper <-> TouchDesigner Bridge for Polygon Mesh Geometry

(c) 2013-2015 

## Authors:

- Gabriel Dunne ([@quilime](http://github.com/quilime/))
- Ana Herruzo  ([@ana00](http://github.com/ana00/))

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
- How to install Grasshopper Plugins (http://coder.the-bac.edu/?p=97)

## Examples

### Sending geometry from Grasshopper -> Touchdesigner

1. Open gh/sender.gh in Grasshopper
2. Open td/receiver.toe in TouchDesigner

#### Grasshopper Sender

gh/sender.gh

![](https://github.com/quilime/gh-td/blob/master/screenshots/gh_sender.PNG)

### TouchDesigner Receiver

td/receiver.toe

![](https://raw.githubusercontent.com/quilime/gh-td/master/screenshots/td_receive.PNG)

### Sending geometry from Touchdesigner -> Grasshopper

1. Open td/receiver.toe in TouchDesigner
2. Open gh/sender.gh in Grasshopper

### TouchDesigner Sender

td/sender.toe

![](https://raw.githubusercontent.com/quilime/gh-td/master/screenshots/td_sender.JPG)

#### Grasshopper Receiver

gh/receiver.gh

![](https://github.com/quilime/gh-td/blob/master/screenshots/gh_receiver.JPG)
 
## Demo Video

[https://vimeo.com/144831795](https://vimeo.com/144831795)



