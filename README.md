# LJOptimization of Additive FF

Contains psfs, pdbs, and calculated props from additive LJ OPT. Here the parameters were obtained from CGENFF and only the LJs are optimized there after. 

**Content of the repo:**

1) pdbs: pdbs of molecules in liquid phase 

2) psfs: psfs of the molecules in liquid and gas phase

3) init_opt_props.xlsx: calculated inital and final values of the molecular properties

4) init_final_param.txt: the initial and optimized values of the additive LJ params

5) equivalent_atomtypes.txt: atomtypes that were treated as equivalent during the optimization (i.e, for atomtypes in a row, their emin and rmin are constrained to be the same during optimization)
