# PorosityGuard
My first project[actually not, i have built more projects before. Maybe more like - first project which is gonna go up on github!] happens to a porosity predictor!! Let's see how it goes...
<br> 
Alright, so I am going to use the following dataset:
"Dataset of X-Ray Micro Computed Tomography Measurements of Porosity for Nominal and Low Power Coupons Fabricated by Powder Bed Fusion-Laser Beam"
on Figshare by Justin Miner, Sneha Prabha Narra...

Alongside a readme file, it has two csv files, named:
parameters.csv and poredf.csv

On merging the two files together on a 'Name' column, we were left with:
484k rows and 11 columns namely:
A.Name
   Description: Denotes the sample that porosity came from by a unique identifier. Links to poredf.csv
B. Power (W)
  Description: Denotes the laser power in watts.
C. Velocity (mm/s)
   Description: Denotes the laser scanning velocity in mm/s
D. Spot Size (um)
   Description: Denotes the laser spot size in micrometers
E. Hatch Spacing (um)
   Description: Denotes the hatch spacing or distance between adjacent scan lines in micrometers
F. Layer Height (um)
   Description: Denotes the amount of powder added per layer in micrometers
G. Geometry
   Description: Denotes the geometry. AX: Axial, 4PB: 4-point bend
H. Volume (mm^3)
	 Description: Denotes the volume scanned using X-ray Micro Computed Tomography in millimeters cubed
I. Name: X (mm)
   Description: Denotes the build plate location from the recoater in mm. Uses EOSM290 coordinate system.
J. Name: Y (mm)
   Description: Denotes the build plate location from the gas flow in mm. Uses EOSM290 coordinate system.
K. Equivalent Spherical Diameter (um)
	 Description: Denotes the diameter of a sphere with equivalent volume .
