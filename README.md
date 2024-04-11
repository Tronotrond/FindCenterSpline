Find Center Spline HDA

This tool aims to solve some of the more typical VFX challenges I've faced when receiving or using models from others. Very often you need, or it would be very helpful to have a spline for different objects. Ropes, wires, pipes, cables etc. which can then be used for dynamic simulations. Or it can be helpful to rebuild a mesh, for cleanliness, UV purposes etc.

Main features of the tool

- Three different methods of finding a center spline from an input object/geometry. Edge loop, primitive loop and step growth.
- Aims to automate the detection of loops and directions automatically
- Calculates the object width (static or varying) and adds pscale attribute to the spline
- Support for curveu and tangentu attributes with or without resampling
- Use original geometry for point generation (center on edge or primitives) or resample curve
- Experimental feature of rebuilding bad input geometry. The tool can try to quad remesh the geometry and find edge loop from end to end from there. Doesn't work well on models with sharp corners though.
