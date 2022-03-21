# ORCA025.L75-MOCCITCLIM
OCCIPUT climatological configuration  with ORCA025.L75

# Reference code
## NEMO
  rev. 4521    of  http://forge.ipsl.jussieu.fr/nemo/svn/trunk 

  svn co -r 4521 http://forge.ipsl.jussieu.fr/nemo/svn/trunk NEMO_3.5beta

## XIOS
  rev. 565 of http://forge.ipsl.jussieu.fr/ioserver/svn/XIOS/branchs/xios-1.0

  svn co -r 565 http://forge.ipsl.jussieu.fr/ioserver/svn/XIOS/branchs/xios-1.0

# Description
 This repository hold the CONFIG directory to be used for reproducing this climatological run.
 
 In MY_SRC there are the fortran modules differing or added to the standard NEMO reference.
 
 cpp_ORCA025.L75-MOCCITCLIM.fcm shows the used CPP keys for this config, and arch_xxx.fcm were used for compilation on OCCIGEN (CINES).
 
 In EXP00, namelists and xml files are given.  Notice that most of the xml files are templates which are concatenated at run time to form the final iodef.xml file ( XIOS_1.0, for this configuration).
