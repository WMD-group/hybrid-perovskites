[![DOI](https://zenodo.org/badge/19191394.svg)](https://zenodo.org/badge/latestdoi/19191394)

# Crystal structures of halide perovskites

A collection of optimised crystal structures of inorganic and hybrid halide perovskites, from density functional theory, including CH<sub>3</sub>NH<sub>3</sub>PbI<sub>3</sub> (MAPI) and [HC(NH<sub>2</sub>)<sub>2</sub>]PbI<sub>3</sub> (FAPI). For conciseness in the file names, methylammonium may be referred to as MA, and formamidinium as FA. 

Calculated phonon data is collected in another [Github repository](https://github.com/WMD-group/Phonons).

Source
------
For the ‘pseudo-cubic’ phases the starting point is a standard cubic ABX<sub>3</sub> perovskite structure (all internal positions fixed by the space group). The 'A' site is replaced by a molecule, which lowers the symmetry and allows distortions of the BX<sub>6</sub> octahedra. The final structures have been obtained following an iterative procedure with small ion displacements (`ISIF = 2` in VASP) using a Quasi-Newton algorithm and the PBEsol exchange-correlation functional. 

_Note:_ A discussion of perovskite structures: http://thelostelectron.wordpress.com/2014/06/22/crystal-structures-of-hybrid-perovskites-are-not-0k//

_N.B._ For property calculations, always re-optimise a crystal structure using your own calculation setup (and exchange-correlation functional). 

Used in
------

- "Structural and electronic properties of hybrid perovskites for high-efficiency thin-film photovoltaics from first-principles" [APL Materials (2013)](http://scitation.aip.org/content/aip/journal/aplmater/1/4/10.1063/1.4824147) 

- "Relativistic quasiparticle self-consistent electronic structure of hybrid halide perovskite photovoltaic absorbers” [Physical Review B (2014)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.89.155204)

- "Atomistic origins of high-performance in hybrid halide perovskite solar cells" [Nano Letters (2014)](http://pubs.acs.org/doi/abs/10.1021/nl500390f)

- "Molecular ferroelectric contributions to anomalous hysteresis in hybrid perovskite solar cells" [APL Materials (2014)](http://scitation.aip.org/content/aip/journal/aplmater/2/8/10.1063/1.4890246)

- "Phase stability and transformations in the halide perovskite CsSnI<sub>3</sub>" [Physical Review B (2015)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.144107) 

- "Assessment of polyanion (BF<sub>4</sub>- and PF<sub>6</sub>-) substitutions in hybrid halide perovskites" [Journal of Materials Chemistry A (2015)](http://pubs.rsc.org/en/content/articlelanding/2015/ta/c4ta05284f#!divAbstract) 

- "Self-regulation mechanism for charged point defects in hybrid halide perovskites" [Angewandte Chemie (2015)](http://onlinelibrary.wiley.com/doi/10.1002/anie.201409740/abstract)

- "The dynamics of methylammonium ions in hybrid organic–inorganic perovskite solar cells" [Nature Communications (2015)](http://www.nature.com/ncomms/2015/150529/ncomms8124/full/ncomms8124.html)

- "Cubic perovskite structure of black formamidinium lead iodide, α-[HC(NH<sub>2</sub>)<sub>2</sub>]PbI<sub>3</sub>, at 298 K" [Journal of Physical Chemistry Letters (2015)](http://pubs.acs.org/doi/abs/10.1021/acs.jpclett.5b01432)

- "Phonon anharmonicity, lifetimes, and thermal transport in CH<sub>3</sub>NH<sub>3</sub>PbI<sub>3</sub> from many-body perturbation theory" [Physical Review B (2016)](http://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.220301)

- "Can Pb-free halide double perovskites support high-efficiency solar cells?"[ACS Energy Letters (2016)](http://pubs.acs.org/doi/abs/10.1021/acsenergylett.6b00471)

- "Screening procedure for structurally and electronically matched contact layers for high-performance solar cells: hybrid perovskites" [Journal of Materials Chemistry A (2016)](http://pubs.rsc.org/en/Content/ArticleLanding/2016/TC/C5TC04091D)

- "Relativistic origin of slow electron-hole recombination in hybrid halide perovskite solar cells" [APL Materials (2016)](http://dx.doi.org/10.1063/1.4955028)

Requirements
------
To open the .cif file, a viewer such as http://jp-minerals.org/vesta/en/.
To run the POSCAR file: a VASP license, and the other required input files (INCAR; KPOINTS and POTCAR)
