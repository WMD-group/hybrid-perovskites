#Hybrid-perovskites

Optimised crystal structures of hybrid halide perovskites, from density functional theory, including CH3NH3PbI3 (MAPI) and [HC(NH2)2]PbI3 (FAPI). For conciseness in the file names, methylammonium may be referred to as MA and formamidinium as FA.

Source
------
For the ‘pseudo-cubic’ phases the starting point is a standard cubic perovskite structure (all internal positions fixed by the space group). The 'A' site is replaced by a molecule, which lowers the symmetry and allows distortions of the BX6 octahedra. The final structures have been obtained following an iterative procedure with small ion displacements (ISIF2 in VASP) using a Quasi-Newton algorithm and the PBEsol exchange-correlation functional. 

_Note:_ A discussion of perovskite structures: http://thelostelectron.wordpress.com/2014/06/22/crystal-structures-of-hybrid-perovskites-are-not-0k//

_N.B._ For property calculations, always re-optimise a crystal structure using your own calculation setup (and exchange-correlation functional). 

Used in
------
- "Structural and electronic properties of hybrid perovskites for high-efficiency thin-film photovoltaics from first-principles" [APL Materials (2013)](http://scitation.aip.org/content/aip/journal/aplmater/1/4/10.1063/1.4824147) 

- "Relativistic quasiparticle self-consistent electronic structure of hybrid halide perovskite photovoltaic absorbers” [Physical Review B (2014)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.89.155204)

- "Atomistic origins of high-performance in hybrid halide perovskite solar cells" [Nano Letters (2014)](http://pubs.acs.org/doi/abs/10.1021/nl500390f)

- "Molecular ferroelectric contributions to anomalous hysteresis in hybrid perovskite solar cells" [APL Materials (2014)](http://scitation.aip.org/content/aip/journal/aplmater/2/8/10.1063/1.4890246)

- "Assessment of polyanion (BF4- and PF6-) substitutions in hybrid halide perovskites" [Journal of Materials Chemistry A (2015)](http://pubs.rsc.org/en/content/articlelanding/2015/ta/c4ta05284f#!divAbstract) 

- "Self-Regulation Mechanism for Charged Point Defects in Hybrid Halide Perovskites" [Angewandte Chemie (2015)](http://onlinelibrary.wiley.com/doi/10.1002/anie.201409740/abstract)

- "The dynamics of methylammonium ions in hybrid organic–inorganic perovskite solar cells" [Nature Communications (2015)](http://www.nature.com/ncomms/2015/150529/ncomms8124/full/ncomms8124.html)

- - "Cubic Perovskite Structure of Black Formamidinium Lead Iodide, α-[HC(NH2)2]PbI3, at 298 K" [Journal of Physical Chemistry Letters (2015)](http://pubs.acs.org/doi/abs/10.1021/acs.jpclett.5b01432)

Requirements
------
To open the .cif file, a viewer such as http://jp-minerals.org/vesta/en/.
To run the POSCAR file: a VASP license, and the other required input files (INCAR; KPOINTS and POTCAR)

Disclaimer
------
This file is not affiliated with *VASP*. Feel free to use and modify, but do so at your own risk.