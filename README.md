# chem-julia
Utilities in Julia for chemistry

[features.csv](https://github.com/burubaxair/chem-julia/blob/main/features.csv) - Properties of chemical elements from the CRC Handbook of Chemistry and Physics (97th Edition).

[ptable.ipynb](https://github.com/burubaxair/chem-julia/blob/main/ptable.ipynb) - Periodic table in Julia which can display the values of some atomic property. You need to supply a DataFrame, in which one column (called "Element") has atomic symbols, and other columns are properties (e.g. electronegativity, ionization energy, etc). Then specify the column to display, the title and the file name to save the picture. In the current example, it shows first ionization energies ("IP") and polarizabilities ("Polariz") from [features.csv](https://github.com/burubaxair/chem-julia/blob/main/features.csv).

