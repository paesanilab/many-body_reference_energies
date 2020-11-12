# many-body_reference_energies
## Contents
This repository contains the reference energies used to train our many-body models.
Please cite the corresponding papers (indicated below) if you use the data.

The folders one-body, two-body, and three-body contain the following items:
- Training and sets set files with all the configurations compiled in a single XYZ file with the binding, nbody energy in the comment line. Some of the oldest sets have different format of the comment line. One-body training set may have only one energy (deformation energy). Two body training sets may have binding, interaction, deformation of mon1, deformation of mon2. Newer training sets will have always binding,n-body energy in this order. The binding energies might not be properly calculated when using counterpoise correction, but since it is only used in the binding, it does not matter.

The inputs and outputs of the electronic structure calculations are available upon request. Just send an email to fpaesani@ucsd.edu asking for them and we will happily provide them.

## Citations to cite if Training and Test sets are used
### H2O -- H2O

### H2O -- H2O -- H2O

### CH4

### CH4 -- H2O 

### CH4 -- CH4

### CO2

### CO2 -- CO2

### CO2 -- H2O

### M+ -- H2O
Where M can be Li, Na, K, Rb, Cs

## Citations to cite if clusters data is used
