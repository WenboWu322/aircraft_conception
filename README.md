# aircraft_conception
This project is to use the multidisciplinary aircraft design python library to build aircraft of many different configurations, using different energy sources and with different top-level design aircraft requirements (TLARs). The author of this performant library is Conceptual Airplane Design & Operations (CADO team), Aircraft & Systems, Air Transport Department, ENAC.

This project consists of two main folders: aircraft and utils.
1. marilib：
  1). airframe
  This package defines the main aircraft components and assembly

  2). design
  The main design processes are defined in this module:  
  * Multidisciplanary Design Analysis 
  * Mulitdisciplinary Design Feasible  
  That will allow you to draw design space charts.

  3). tool
  You can also define your own settings here.
  For example, the Top Level Aircraft Requirement can be specified as follow :
  requirement =  Requirement(n_pax_ref = 150,design_range = unit.m_NM(3000.), # convert Nautical Miles to meters
  cruise_mach = 0.78, cruise_altp = unit.m_ft(35000.))  # convert feets to meters 

2. utils.
  Packages about geography settings, math tools, optimization tools, etc.


In the example folder are two customized aircrafts where we set up the geometry, fuel type, other technical parameters, etc. to meet the needs of the project.
  
The example results folder is a set of graphs of the results of several examples.
