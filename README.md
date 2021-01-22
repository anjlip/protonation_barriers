# protonation_barriers

This project contains raw data used to compute electrochemical protonation barriers for C, N, and O adsorbates on late transition metals.
Data includes structures along the reaction pathway computed via the MLNEB algorithm and DFT, as described in (add publication info)

The data is organized as follows:
- ./adsorbate/metal_surface/rxn_path: contains trajectory files for each reaction path with subdirectories corresponding to each adsorbate and metal surface
- ./adsorbate/metal_surface/true_IS: contains structure of true initial state used for barrier computation - water structure (without hydronium) and unprotonated adsorbate on the surface
