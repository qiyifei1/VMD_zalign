# VMD_zalign
A VMD script to align a membrane protein using RMSD alignment by rotating around Z axis only.

In membrane protein simulations, it is sometimes useful to align the protein in the XY plane (membrane normal is Z axis) by rotating around the Z axis only. This VMD script finds the best rotation angle that has the minimal RMSD value and align the protein in a DCD file to a reference structure.
