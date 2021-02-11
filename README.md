# HIC_experimental_data
This repository is intended as a place to store experimental data relevant to Heavy Ion Physics in a consistent format. 

Data are stored in a directory format:

The top level directory is the Experimental System, named according to `<Projectile>-<Target>-<$\sqrt{s}$[GeV]>` 

e.g. Pb Pb collisions at $\sqrt{s} = 2.76$ TeV are stored in a folder named `Pb-Pb-2760`

The immediate subdirectory is the name of the experimental collaboration who reported the result.

Finally, inside the folder of each experiment, the file is named according to the observable, with appropriate headers to give the reference and to delimit each column.

Additional information for references can be found in the references.md document (if it exists).

