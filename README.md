# MG3
Morrison-Gettelman Microphysics, Version 3 (MG3)

Open source code for Cloud Microphysics Scheme 'MG3'. Initial commit for reference. 

Represents version from CAM development trunk:

https://svn-ccsm-models.cgd.ucar.edu/cam1/trunk_tags/cam6_1_033/components/cam/src/physics/cam/

References: 

Gettelman, A., H. Morrison, K. Thayer‐Calder, and C. M. Zarzycki. 2019. The Impact of Rimed Ice Hydrometeors on Global and Regional Climate. Journal of Advances in Modeling Earth Systems. https://doi.org/10.1029/2018MS001488.


Gettelman, A. and H. Morrison, Advanced Two-Moment Microphysics for Global Models. Part I: Off line tests and comparisons with other schemes. J. Climate, 28, 1268-1287. doi: 10.1175/JCLI-D-14-00102.1, 2015.

Gettelman, A., H. Morrison, S. Santos, P. Bogenschutz and P. H. Caldwell. Advanced Two-Moment Microphysics for Global Models. Part II: Global model solutions and Aerosol-Cloud Interactions. J. Climate, 28, 1288-1307. doi:10.1175/JCLI-D-14-00103.1 , 2015. 

Basic structure:

micro_mg3_0.F90        : core code, includes initialization and timestep routines
micro_mg_utils.F90     : process rate and size distribution functions
micro_mg_data.F90      : extra utilities for CAM
micro_mg_cam.F90       : Interface for the Community Atmosphere Model version 6 (CAM6)
wv_saturation.F90      : CAM water vapor routines
wv_sat_methods.F90
       
for questions contact Hugh Morrison, Andrew Gettelman e-mail: morrison@ucar.edu, andrew@ucar.edu
