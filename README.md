# The Origins of the CGM Visualized

This repository contains [online interactive visualizations of the CGM](https://zhafen.github.io/CGM-fates), using data from Hafen et al. (2019). These visualizations were developed using [Firefly](https://github.com/ageller/Firefly).

When you first start the visualization you can select a simulation, redshift, and type of visualization you would like to view. The simulations available were created as part of the [FIRE project](https://fire.northwestern.edu). Two redshifts are available per simulation: `lowz` and `highz` corresponding to z=0.25 and z=2 respectively. The tags at the end indicate whether or you will see a "snapshot" or "pathlines" visualization.

*Snapshot of the CGM Visualizations:*
These visualizations display ~1e5 particles at the specified redshift and sampled out to within the virial radius, as described in Hafen et al. 2019. Each particle is colored according to their origin:

*Pathlines of CGM Gas Visualizations:*
These visualizations display the full pathlines, over the course of the entire simulation, for 400 particles. Each particle was in the CGM of the specified simulation at the specified redshift. Each particle is colored according to how it arrived in the CGM (i.e. its origin). These visualizations are the 3D equivalent of a figure like Figure 4 in Hafen et al. (2019). We display the pathlines of 100 particles per origin, of which there are four:

1. Accreted onto Central (blue) - gas that will next accrete onto the central galaxy.
2. Accreted onto Satellite (purple) - gas that will next accrete onto a satellite galaxy.
3. Ejected into IGM (red) - gas that will next be ejected into the IGM.
4. Remains CGM (yellow) - gas that will remain in the CGM until z=0.

There are a few additional things to note

* All distances are in proper kpc relative to the central galaxy.
* A ruler (100 kpc on a side with 1 kpc spacing between points) can be toggled on and off.
* A secondary ruler points along the total angular momentum of the stars and is 50 kpc long, with 1 kpc spacing between points. This ruler is accompanied by a disk with a radius corresponding to the galaxy radius, defined as four times the stellar half mass radius.
* Clicking on the downward arrow next to a classification allows one to filter the data according to a variety of options.
