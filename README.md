# vmd testcase of a large objet

Tru <tru@pasteur.fr>

## Why ?
- pushing vmd limits with a large representation
- testcase for remote visualisation (minimal 15 FPS)

## Usage
- download the stmv.pdb.gz and stmv.vmd files in the working directory
- uncompress the pdb file `gunzip stmv.pdb.gz`
- start vmd with: `vmd -e stmv.vmd`

## References
- https://www.ks.uiuc.edu/Research/namd/utilities/stmv/stmv.pdb.gz (LICENSE?)
- VMD: https://www.ks.uiuc.edu/Research/vmd/
```
-rw-r--r--. 1 tru Bis 82M Feb 14 13:36 stmv.pdb
-rw-r--r--. 1 tru Bis 15M Dec  7  2005 stmv.pdb.gz
-rw-r--r--. 1 tru Bis 29K Feb 14 13:51 stmv.vmd
```

## Caveat
- plain ribbon representation without water
- rendering can be very demanding for your hardware, depending
on the representation chosen.

## Improvements
- prepare rendering for chimera/chimerax/pymol/...
