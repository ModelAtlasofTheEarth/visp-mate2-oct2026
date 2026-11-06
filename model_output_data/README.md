# Model Output Data

**Note Output Data will often be too large to host on Github.** 

To access output data for this model, check the M@TE collection on NCI (http://dx.doi.org/10.25914/yrzp-g882), or refer to this model on the M@TE website (http://mate.science)


## Notes:
The model output data is stored in a hdf5 format. You will see a h5 folder and a series of xdmf files.

h5 folder contains the hdf5 data, all the information computed by the model are stored in these files. You will have at least the tin (surface) and flow (stream network) dataset and also the sed (stratigraphy) data if the stratal structure is computed in your simulation.

two .xdmf files for the surface (tin_series.xdmf) and the flow network (flow_series.xdmf) that read the xmf files through time.