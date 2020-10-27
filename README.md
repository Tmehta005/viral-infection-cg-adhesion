# Viral_Infection_CG_Adhesion
Coarse-Grain Dynamice Model for Virus-Host Cell Interactions during cellular adhesion and entry. The square section of the membrane domain is represented as the beads connected with springs. Each os the bead is connected to its 6 neighbors, except for the ones at the end. Virus is represented as an analytical spherical surface.
Spherical_100.py: It is the driver for the case of spherical virions, like Corona along with the Brownian dynamics calculations to describe the folding of the membrane around the virus. This file reads the inputs from an input file membrane_100.xlsx and imports the functions from Graph_def.py. This main program performs the calculations at 5 different Temperatures (K) (280, 290, 300, 310, 320) and six different values of membrane tension (pN) (0, 50, 100, 150, 200, 250) and writes the output in the locationout_3D.xls 
The output file has two different output - (a) the time-dependent average proximity of the membrane from the virus for each of the Temperature-Tension combinations (b) The steadystate values of the proximity index and time to attach.
