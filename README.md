
# Section Cut

A Blender add-on. Put a plane where you want the cut, press once, and get
the section as real geometry: closed outlines, a capped face, and the area
of every loop.

The outline comes out as a curve you can dimension or send to CAD. The
filled face is what makes a section read as solid rather than hollow.

It reads the triangles directly rather than using a boolean, so it does not
fail on the open and single sided shells that imported models are full of.
Checked against a sphere: the section area came within a third of a percent
of the exact circle at every height tried, including a tilted plane.

It does not update as you drag. That was tried and dropped rather than
shipped half working.

## Install

Download the zip and use Edit > Preferences > Get Extensions >
Install from Disk.

## Requirements

Blender 4.2 or newer. Only numpy, which ships with Blender.

## License

GPL-3.0-or-later
