# FB18CMAP
Phosphorylation Modification Force Field FB18CMAP Improving Conformation Sampling of Phosphoprotein

# Usage

## Prepare FB18 topology files

* The force field parameters of AMBER-FB18 are given in the 2021 JPCB paper available here: https://pubs.acs.org/doi/10.1021/acs.jpcb.1c07547((http://www.cnblogs.com/sxdcgaq8080/p/7894828.html))

* A sample file is available at `sample/SEP.top`

## Add CMAP parameters

* Put `sample/SEP.top` and `ADD_CMAP.py` in the working directory

* Use the command line: `python ADD_CMAP.py -p SEP.top -c fb18cmap.para -o SEP_cmap.top -s`

* The output sample file is available at `sample/SEP_cmap.top`.
