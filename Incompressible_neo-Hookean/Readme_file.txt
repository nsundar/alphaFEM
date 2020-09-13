!The files in Incompressible neo-Hookean cantilever beam folder explain 
preprocessing and analysis using proposed Alpha-FEM Abaqus UEL
----------------------------------------------------------------------------
# Preprocessing task
Node_AdjNodes_code - MATLAB code for finding attached nodes for the node
under consideration and this also generates correspong UEL files.
UEL definitions are written in seperate dat files. Please refer
U1_nodes, U2_nodes etc. files for reference.

Elements.dat 		- Supporting files for running MATLAB code
Node_COORDS.dat 	- Supporting files for running MATLAB code
get_nod_adjele.m	- Supporting files for running MATLAB code
U1_nodes, U2_nodes etc. - Output files from MATLAB code
----------------------------------------------------------------------------
# Analysis using Abaqus NSFEM UEL
AFEM_UEL_nonlinear		- Proposed UEL FORTRAN code
mesh.dat			- Data file for running Alpha-FEM Abaqus UEL
---------------------------------------------------------------------------