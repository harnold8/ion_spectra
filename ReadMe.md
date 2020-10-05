## Data Format
* "*.silo" files are best ploted with VisIt, open source software available at https://wci.llnl.gov/simulation/computer-codes/visit/

* "*.rar" are the files which contain the particle data. The extracted file is structured as follows:

## Extraction
* x-coordinate[R_E] y-coordinate[R_E] z-coordinate[R_E] x-coordinate_on_trajectory[R_E] y-coordinate_on_trajectory[R_E] z-coordinate_on_trajectory[R_E] distance_to_trajectory[R_E] v_x[m/s] v_y[m/s] v_z[m/s] v^2[m^2/s^2] weight[particle number/upstreamdensity] species_number
* weight*upstreamdensity= number of particles corresponding to the macro particle 

* species_number: 
   0 - upstream plasma
   1 - molecular oxygen
   2 - water vapor
