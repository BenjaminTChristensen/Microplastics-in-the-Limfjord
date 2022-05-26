# Microplastics in the Limfjord Project
The project is a semester project conducted on the second semester of the master in 'Water and Environmental Engineering' at Department of the Built Environment at Aalborg University.

The model is for the Eastern part of the Limfjord, an estuary located in the Northern Jutland of Denmark, and is based on the DHI's software MIKE 3, combined with water level data provided by DMI, stream discharge from Vandportalen, and microplastic concentrations found in Norwegian Rivers. The scope is to determine placement for further microplastic sampling regarding the water surface and the sediments in the Limfjord.

The main file is 'EastFjord.m3fm', which requires some inputs from other files, mainly stored as dfs0-files. The files are based on their use in the software:
  1. Model Domain - 'EastLimfjord3.mesh' which is the overall boundary of the model in which the calculations are done.
  2. Boundary Conditions - 'Hals_Havn.dfs0' and 'WestBound.dfs1' which are the boundaries for the east and west, respectively.
  3. Wind Forcing - 'Tylstrup_Wind.dfs0' which is the wind data for the model.
  4. Discharge - This branch contains the measured discharges from the five used streams. All as dfs0-files.
  5. Microplastic - This branch contains the discharged amount of microplastic particles into the system. The files are based      upon the polymer type, combined with the used stream, with a daily discharge in a single month ('_september') to not clog      the Limfjord in a yearly simulation with particles and an hourly discharge for the monthly simulations ('_hourly').

The model calculates the placement of the microplastics which are further analyzed in order to visualize the results as seen in the report.

