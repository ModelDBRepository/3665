NEURON mod files for the Ih current from the paper:
Cadetti L, Belluzzi O.
Hyperpolarisation-activated current in glomerular cells 
of the rat olfactory bulb.
Neuroreport 12:3117-20 (2001).

Running the kinetics.hoc simulation file will show 
the activation steady-state, the time constant, a simple simulation
using a somatic current injection, and a family of curves
generated modeling the same protocol used in the experiments. 

Markers show the time constants reported in Fig.1c' of the paper.
 
By reducing the ghbar parameter to 0
one can model the Ih block by Cesium as in Fig.1a'.
 
Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows using NEURON 5.2:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on how to use this model should be directed to
michele.migliore@pa.ibf.cnr.it
