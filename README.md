# protonation_barriers

This project contains raw data used to compute electrochemical protonation barriers for C, N, and O adsorbates on late transition metals.
Data includes structures along the reaction pathway computed via the MLNEB algorithm and DFT, as described in (add publication info)

The data is organized as follows:
- Adsorbate (C, N, O)
  - Metal (Ru, Ir, Pd, Rh, Pt)
    - Water structure (H-up, H-down)
      - path.traj: Atomic simulation environment (ASE) trajectory file for each reaction path
      - true_IS.POSCAR: structure of true initial state used for barrier computation - water structure (without hydronium) and unprotonated adsorbate on the surface
