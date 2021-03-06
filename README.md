# Walkabout Version 1 (LA-CC-11-033) (Open Source) 
 
[![Build Status](https://travis-ci.org/lanl/walkabout.svg?branch=master)](https://travis-ci.org/lanl/walkabout)
 
Performs random walk particle tracking simulations of solute transport based on groundwater flow solutions that use fully unstructured control volume grids. Walkabout 1.0 is designed to work within the FEHM (Zyvoloski, 2007) code system, and accepts groundwater flow solutions from FEHM and computational mesh descriptions from LaGrit (Los Alamos Grid Toolbox).

A typical workflow for Walkabout within the FEHM system would use LaGrit to generate unstructured grids. FEHM then provides a discretized representation of the steady-state flow field to Walkabout. Given this discrete solution, Walkabout then reconstructs a groundwater flow field, and performs the random walk particle tracking calculation. Output is provided in a form compatible with the PLUMECALC software. PLUMECALC may be used to efficiently post-process the particle tracking results from Walkabout to add effects of retention/retardation and arbitrary source histories. An option exists to also record particle positions versus time, thus allowing other post-processing codes or visualization systems to be used.

## Documentation - Walkabout (V1) LA-UR-11-01952

__Update in Progress__
[Walkabout Documentation](https://lanl.github.io/walkabout/index.html)

__2011 PDF__
[Scott Painter's User's Manual](https://github.com/lanl/walkabout/blob/master/docs/walkaboutUM.pdf)


## License

[External Contributor Agreement (Non-LANL Employees)](https://www.clahub.com/agreements/lanl/walkabout)
   
[Copyright text for Walkabout](./COPYRIGHT.md)


## Installation
    
[Install directions for Walkabout](./INSTALL.md)
