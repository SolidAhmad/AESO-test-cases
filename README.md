# AESO test cases

The files contain data for an aggregated and reduced Alberta Electric System Operator (AESO) system to a 6-bus test case with 6-branches, and a reduced 144-bus AESO system including only the 240kV and 138kV corridors as done by AESO following a realistic planning test case.
The test cases include geometrical data and the spatial mapping is identical to the real AESO network. 

The test case is intended for Power System Transition Planning and is suitable for DCPF, DCOPF, and GTEP. 
The Excel file contains three sheets providing the substation, branch, and unit details. 
The columns containing geometrical data includes co-ordinates of points and paths that are meant to be used by the shapely or geopandas module in python. However, it can easily be formatted to use on any software. 

![AESO-144 eps](https://github.com/user-attachments/assets/0ee281b7-416b-43fe-a49d-6f04b0d8a924 | width=100)
