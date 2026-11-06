# PorosityGuard
My first project[actually not, i have built more projects before. Maybe more like - first project which is gonna go up on github!] happens to a porosity predictor!! Let's see how it goes...
<br> 
Alright, so I am going to use the following dataset:
<br>
"Dataset of X-Ray Micro Computed Tomography Measurements of Porosity for Nominal and Low Power Coupons Fabricated by Powder Bed Fusion-Laser Beam"
on Figshare by Justin Miner, Sneha Prabha Narra...
<br>
Alongside a readme file, it has two csv files, named:
parameters.csv and poredf.csv
<br>
On merging the two files together on a 'Name' column, we were left with:
<br>
484k rows and 11 columns namely:
<br>
A.Name
<br>
   Description: Denotes the sample that porosity came from by a unique identifier. Links to poredf.csv
<br>
B. Power (W)
<br>
   Description: Denotes the laser power in watts.
<br>
C. Velocity (mm/s)
<br>
   Description: Denotes the laser scanning velocity in mm/s
<br>
D. Spot Size (um)
<br>
   Description: Denotes the laser spot size in micrometers
<br>
E. Hatch Spacing (um)
   <br>
   Description: Denotes the hatch spacing or distance between adjacent scan lines in micrometers
<br>
F. Layer Height (um)
   <br>
   Description: Denotes the amount of powder added per layer in micrometers
<br>
G. Geometry
<br>
   Description: Denotes the geometry. AX: Axial, 4PB: 4-point bend
<br>
H. Volume (mm^3)
   <br>
   Description: Denotes the volume scanned using X-ray Micro Computed Tomography in millimeters cubed
<br>
I. X (mm)
   <br>
   Description: Denotes the build plate location from the recoater in mm. Uses EOSM290 coordinate system.
<br>
J. Y (mm)
   <br>
   Description: Denotes the build plate location from the gas flow in mm. Uses EOSM290 coordinate system.
<br>
K. Equivalent Spherical Diameter (um)
<br>
   Description: Denotes the diameter of a sphere with equivalent volume .
