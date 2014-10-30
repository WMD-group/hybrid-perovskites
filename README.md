Hybrid-perovskites
==================

DFT optimised crystal structures of hybrid halide perovskites, including CH3NH3PbI3 (MAPI).

Source
------------

For the ‘pseudo-cubic’ phases the starting point is a standard cubic perovskite structure (all internal positions fixed by the space group). The 'A' site is replaced by a molecule, which lowers the symmetry and allows distortions of the BX6 octahedra. 

The final structures have been obtained following an iterative procedure with small ion displacements (ISIF2 in VASP) using a Quasi-Newton algorithm and the PBEsol exchange-correlation functional within Density Functional Theory (DFT). 

Note: A discussion of perovskite structures: http://thelostelectron.wordpress.com/2014/06/22/crystal-structures-of-hybrid-perovskites-are-not-0k//

N.B. For property calculations, always re-optimise a crystal structure using your own calculation setup (and exchange-correlation functional). 

Used in
------------
- "Structural and electronic properties of hybrid perovskites for high-efficiency thin-film photovoltaics from first-principles" APL Materials (2013) DOI: 10.1063/1.4824147

- "Relativistic quasiparticle self-consistent electronic structure of hybrid halideperovskite photovoltaic absorbers” Physical Review B (2014) DOI: 10.1103/PhysRevB.89.155204

- "Atomistic origins of high-performance in hybrid halide perovskite solar cells" Nano Letters (2014) DOI: 10.1021/nl500390f

- "Molecular ferroelectric contributions to anomalous hysteresis in hybrid perovskite solar cells" APL Materials (2014) DOI: 10.1063/1.4890246

- "Assessment of polyanion (BF4- and PF6-) substitutions in hybrid halide perovskites" Journal of Materials Chemistry A (2014) DOI: 10.1039/C4TA05284F

- "Band alignment of the hybrid halide perovskites CH3NH3PbCl3, CH3NH3PbBr3 and CH3NH3PbI3" Materials Horizons (2014) DOI: 10.1039/C4MH00174E 

Requirements
------------
To open the .cif file, a viewer such as http://jp-minerals.org/vesta/en/.
To run the POSCAR file: a VASP license, and the other required input files (INCAR; KPOINTS and POTCAR)

Disclaimer
----------
This file is not affiliated with *VASP*. Feel free to use and modify, but do so at your own risk.